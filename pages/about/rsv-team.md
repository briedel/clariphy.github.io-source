---
permalink: /about/rsv-team.html
layout: default
title: CLARIPHY RSV Team
---

<div class="container-fluid">
  <h1>CLARIPHY RSV Team</h1><br>
  <div class="row">
  {% for member in site.data.orgs.rsv-team.personnel  %}
     {% assign person = site.data.people[member] %}
       <div class="card" style="width: 12rem;">
         <img class="card-img-top" src="{{person.photo}}" alt="Card image cap">
         <div class="card-body d-flex flex-column">
         <div class="card-text">
         <b><a href="{{person.website}}">{{person.name}}</a></b><br>
         <small>{{person.institution}}</small><br><br>
         </div>
         <div class="card-text mt-auto"><i>{{person.title}}</i><br></div>
         </div>
       </div>
  {% endfor %}
  </div>
  <br>
</div>
