---
layout: post
title: FM Fact Label
date: 2024-09-27 00:00:00 +0300
description: Online tool providing configurable and interactive visualization of characterizations (metrics) of feature models. 
# Add post description (optional)
img: fmfactlabel.png # Add image post (optional)
tags: [Programming, Learn] # add tag
---
Online tool providing configurable and interactive visualization of characterizations (metrics) of feature models. Collaboration between UMA and US.

Nemo2 is a boolean and numerical constraint language and tool with first-class support for numerical feature modeling based in a collaboration between Universidad de Malaga and University of Texas in Austin.

Nemo2 support extending classic variability models with numerical features and arithmetic in the formats DIMACS and Universal Variability Language (UVL)

Numerical Feature Models (NFMs) must be defined in Nemo2 by using Nemo's modeling language in a .txt file.

Nemo2 transforms and optimize NFMs by means of Bit-Blasting into classic variability models which then are supported by any first-order logic reasoner.

Nemo2 outputs support three formats: a) a UVL model, b) a propositional formula, and c) a Tseitin’s Conjunctive Normal Form (CNF) propositional formula. Besides the transformed model, we make use of comment lines to identify each original feature name and domain (i.e., boolean or numerical) with their respectives bit-blasted features.

Nemo2 is a cross-platform tool that have been developed in Python 3.11.x.

[Go to page](https://fmfactlabel.adabyron.uma.es/)

[Paper](https://dl.acm.org/doi/10.1145/3503229.3547025)