---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Learning VAA: A new method for matching users to parties in voting advice
  applications'
subtitle: ''
summary: ''
authors:
- Guillermo Romero Moreno
- Javier Padilla
- Enrique Chueca
tags:
- e-democracy
- election studies
- issue voting
- machine learning
- spatial model
- vote choice
- Voting advice applications
categories: []
date: '2022-04-01'
lastmod: 2023-02-20T11:34:07Z
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2023-02-20T11:34:07.203187Z'
publication_types:
- '2'
abstract: Voting Advice Applications (VAAs) aim to increase voters’ political competence
  by providing them with the closest political party according to their preferences.
  To do this, VAAs usually compare and aggregate the positions of users and political
  parties on a set of policy issues by defining a conceptual space and some distance
  metric on it. In this paper, we argue that the main method for performing the comparison
  adapts to users’ preferences unsatisfactorily because 1) they use unjustified a
  priori decisions for weighting policy issues and 2) they employ the same issue-voting
  space on all policy issues. Some exceptional cases address these issues by providing
  a community-based recommendation, but often come with lack of interpretability.
  To fill these gaps, we propose an adaptive algorithm that learns the configuration
  of the conceptual space from users’ answers. We employ a hybrid VAA that uses expert
  coding for the party positions and users’ data to adjust the calculation of the
  distance between users and parties. This new matching method, the Learning VAA,
  innovates by adjusting the saliency and issue-voting space for every policy issue.
  We argue and empirically demonstrate that our model fits better the users’ preferences
  while providing a higher degree of interpretability.
publication: '*Journal of Elections, Public Opinion and Parties*'
doi: 10.1080/17457289.2020.1760282
links:
- name: URL
  url: https://doi.org/10.1080/17457289.2020.1760282
---
