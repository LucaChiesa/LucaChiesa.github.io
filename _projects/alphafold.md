---
layout: post
title: AlphaFold @ GPCRs
description: Applying AlphaFold to GPCRs
---

Deep learning models for 3D protein structure prediction have increased the applicability of structure-based drug design to the entire human proteome.
**AlphaFold** and **AlphaFold-Multimer** are the two most important tools for such task but they are limited in their ability to model targets characterized by distinct conformational states.
G-protein coupled receptors (GPCRs) are one of the most important targets in drug discovery and they are characterized by two main conformational states: an active state, and an inactive state.
Different methods have been developed to sample the conformational space and force a specific state for different protein targets, with a particular focus of GPCRs.

To facilitate multistate modelling using AlphaFold I developed [LIT-AlphaFold](https://github.com/LIT-CCM-lab/LIT-AlphaFold), a modified input preparation and prediction pipeline of AlphaFold which incorporates most of the state of the art methods.

Related publications
--------------------

Coming soon