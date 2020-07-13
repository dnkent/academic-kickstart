---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Dissertation: Essays on Machine Learning in International Conflict and Social Networks"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2020-03-15T17:20:37-04:00
lastmod: 2020-03-15T17:20:37-04:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

# To remove bio
profile: false 

# Remove links
share: false
---

+ Chapter 1: [Measuring International Dissatisfaction](/files/kent_ch1.pdf)

+ Chapter 2: [Predicting International Conflict and Revision](/files/kent_ch2.pdf)

+ Chapter 3: [Estimating Heterogeneous Spillover Effects](/files/kent_ch3.pdf)

This dissertation leverages developments in machine learning methods to better model networked social processes, with an emphasis on international politics. The first chapter develops a dataset with estimates for every country's level of dissatisfaction with the international system from 1816-2012. The second chapter takes these dissatisfaction measures and uses them as features in a machine learning model which predicts international conflict onset. The third chapter explores spillover effects in social networks, demonstrating how causal forests can be employed to uncover spillover effect heterogeneity. Across these chapters, machine learning techniques are instrumental in modeling outcomes of interest and leveraging information from social networks.

In the first chapter, I propose a novel measure of international dissatisfaction spanning from 1816 to 2012 which explicitly operationalizes Gilpin's framework: the difference between a state's expected and actual benefits from the international status quo. I estimate a state's expected international benefits by building upon recent efforts to train machine learning ensembles on war outcomes, which I then use to weight a state's observable material capabilities. I estimate actual international benefits by averaging across a state's centrality in valued international networks. The measure provides multiple advantages over alternative estimates both conceptually and statistically. Beyond its conceptual value, the measure's association with militarized conflict is robust to model specifications, unlike the current go-to measure when modeling country-level sentiments: ideal point estimates from United Nations voting records.

The second chapter asks: when do revisionist states occur? Most responses to this question fall under one of three categories: 1) differential growth rates, 2) domestic political changes, or 3) international dissatisfaction. While these arguments are all based on rich research traditions, it is an open question as to which theory best predicts when revision occurs. In order to provide such an empirical comparison, I build a series of machine learning ensembles that predict interstate conflict onset and vary only in the included features. While the models for each of the three theories unsurprisingly demonstrate meaningful predictive capacity, the ensemble based on measures of international dissatisfaction is more accurate than counterparts based on differential growth rates and domestic political changes. The paper's results do not invalidate theories of rising powers and revolutionary regimes, but they do emphasize a greater focus on a state's standing within the broader international system.

The final chapter develops a procedure for estimating heterogeneous spillover effects. In social environments, interference between units is likely the norm, not the exception. This poses a problem for estimating causal effects, where the potential outcomes framework assumes that one unit's treatment assignment has no effect on another unit's outcome. In response to this concern, one increasingly popular approach for handling interference between units is the estimation of spillover effects, where sharing a networked tie to a treated unit confers indirect treatment exposure. However, like average treatment effects, there are good reasons to expect that spillovers vary in magnitude and direction across contexts. In order to capture this variation, I approach spillovers through the lens of heterogeneous treatment effects, which can be modeled with causal random forests