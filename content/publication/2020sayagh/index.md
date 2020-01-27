---
title: "What should your run-time configuration framework do to help developers?"
authors:
- Mohammed Sayagh
- Noureddine Kerzazi
- admin
- Khalil Bennani
- Bram Adams

date: "2020-01-17T00:00:00Z"
doi: "10.1007/s10664-019-09790-x"

# Schedule page publish date (NOT publication's date).
publishDate: "020-01-17T00:00:00Z"
 
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Empirical Software Engineering
publication_short: EMSE

abstract: The users or deployment engineers of a software system can adapt such a system to a wide range of deployment and usage scenarios by changing the value of configuration options, for example by disabling unnecessary features, tweaking performance-related parameters or specifying GUI preferences. However, the literature agrees that the flexibility of such options comes at a price: misconfigured options can lead a software system to crash in the production environment, while even in the absence of such configuration errors, a large number of configuration options makes a software system more complicated to deploy and use. In earlier work, we also found that developers who intend to make their application configurable face 22 challenges that impact their configuration engineering activities, ranging from technical to management-related or even inherent to the domain of configuration engineering. In this paper, we use a prototyping approach to derive and empirically evaluate requirements for tool support able to deal with 13 (primarily technical) configuration engineering challenges. In particular, via a set of interviews with domain experts, we identify four requirements by soliciting feedback on an incrementally evolving prototype. The resulting “Config2Code” prototype, which implements the four requirements, is then empirically evaluated via a user study involving 55 participants that comprises 10 typical configuration engineering tasks, ranging from the creation, comprehension, refactoring, and reviewing of configuration options to the quality assurance of options and debugging of configuration failures. A configuration framework satisfying the four requirements enables developers to perform more accurately and more swiftly in 70% and 60% (respectively) of the configuration engineering tasks than a state-of-the-practice framework not satisfying the requirements. Furthermore, such a framework allows to reduce the time taken for these tasks by up to 94.62%, being slower for only one task.

# Summary. An optional shortened abstract.
summary: The “Config2Code” prototype, which implements the four requirements, is then empirically evaluated via a user study involving 55 participants that comprises 10 typical configuration engineering tasks, ranging from the creation, comprehension, refactoring, and reviewing of configuration options to the quality assurance of options and debugging of configuration failures.

tags:
- Config2Code
- Configuration
- Empirical SE
featured: true

links:
- name: ScienceDirect
  url: https://link.springer.com/article/10.1007/s10664-019-09790-x

#url_pdf: /publication/2020sayagh/2020Sayagh.pdf
#url_code: ''
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Illustration of requirement R1 (Options-as-Code) using the syntax of Config2Code'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- Config2Code
---
