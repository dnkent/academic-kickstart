---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Randomization Approach to Dynamic Analysis of Panel Data"
subtitle: ""
summary: "Under review, paper available upon request"
authors: [With James Wilson (University of San Francisco) and Skyler Cranmer]
tags: []
categories: []
date: 2019-08-05T15:15:01-04:00
lastmod: 2019-08-05T15:15:01-04:00
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
---

Across the social sciences scholars regularly pool effects over substantial periods of time,
a practice that produces faulty inferences if the underlying data generating process is dy-
namic. To help researchers better perform principled analyses of time-varying processes,
we develop a two-stage procedure based upon statistical randomization techniques. Given
panel data, we break the role of time through randomization and produce null distributions
that reflect a time-invariant data generating process. These null distributions serve as a ref-
erence point for the observed trends over time, enabling the quantification of time-varying
effects and the detection of where changes in effects occur. Through a Monte Carlo simu-
lation study, we find that our randomization technique outperforms cutting-edge software
for Bayesian changepoint analysis. A particular benefit of our method is that, by estab-
lishing the bounds for time-invariant effects before interacting with actual estimates over
time, it is able to differentiate gradual changes from effects with a stable mean but high
variance. We also demonstrate the method’s utility by applying it to a popular study on the
relationship between alliance types and the initiation of militarized interstate disputes. The
example illustrates how the technique can help researchers make inferences about where
changes occur in dynamic relationships and ask important theoretical questions about the
causes and consequences of such changes.
