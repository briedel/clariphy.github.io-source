---
permalink: /projects/didacts.html
layout: project
title: DIDACTS
shortname: didacts
description: Data-Intensive Discovery Accelerated by Computational Techniques for Science (DIDACTS)
website: https://didacts.org
team:
  - SigProcessing
  - tunnell
  - Shatkay
awards:
  - type: NSF
    number: OAC-1940074
  - type: NSF
    number: OAC-1940209
---

The purpose of DIDACTS is to pioneer the data science and machine learning algorithms needed to enable discovery in the physical sciences, specifically by pursuing physics-informed machine learning.  Specifically, current state-of-the-art approaches are often unable to include known priors and physical constraints, while also not often providing uncertainties posterior distributions.   An interdiscplinary appraoch to this problem aims to advance both computational methods and fundamental research by having collaborators who are from electrical and computer engineering, computer and information sciences, and astroparticle physics.

DIDACTS has chosen to use the [XENONnT experiment](https://xenonnt.org) as an example of an experiment at the forefront of difficult measurements within particle physics.  The simplicity of this experiment relative to normal particle physics experiments make it more dependent on the data science and machine learning methods used to extract the optimal amount of information from the experiment.  Discoveries made by XENON1T ranged from observing the longest halflife ever measured to observing anamolous electronic recoils.  However, it is best known for being the most sensitive direct detection dark matter to date.  

Within DIDACTS, we are exploring two key thrusts.  One centers on graph machine learning to create architectures more representative of the underlying science, while allowing these algorithms to self-learn the geometry and detector physics, and also allow the inclusion of physical contraints and learning from data.  The other thrust centers on the concept uncertainty, which is the key ingredient of any science measurement, and how we can enable machine learning algorithms to communicate their uncertainty when seeing new data.

Both of these thrusts are trying to tackle core science questions, which also serve as our way to evaluate our methods.  We aim to overcome so-called 'surface events' caused by reconstruction not knowing about the detector geometry, where this is one of the biggest steps we can make to advance our dark matter analysis.  The second science question is neutrinoless double-beta decay, where our reconstruction resolution is directly related to our sensitivity to this process, and which tells us fundamental properties of the neutrino.  
