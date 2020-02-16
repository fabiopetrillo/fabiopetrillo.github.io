---
title: "A large scale empirical study of the impact of Spaghetti Code and Blob anti-patterns on program comprehension"
authors:
- Cristiano Politowski
- Foutse Khomh
- Simone Romano
- Giuseppe Scanniello
- admin
- Yann-Gaël Guéhéneuc
- Abdou Maiga
date: "2020-02-06T00:00:00Z"
doi: "10.1016/j.infsof.2020.106278"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-02-06T00:00:00Z"
 
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Journal of Information and Software Technology
publication_short: IST

abstract: Context - Several studies investigated the impact of anti-patterns (i.e., “poor” solutions to recurring design problems) during maintenance activities and reported that anti-patterns significantly affect the developers’ effort required to edit files. However, before developers edit files, they must understand the source code of the systems. This source code must be easy to understand by developers. Objective - In this work, we provide a complete assessment of the impact of two instances of two anti-patterns, Blob or Spaghetti Code, on program comprehension. Method - We analyze the impact of these two anti-patterns through three empirical studies conducted at Polytechnique Montré al (Canada) with 24 participants; at Carlton University (Canada) with 30 participants; and at University Basilicata (Italy) with 79 participants. Results - We collect data from 372 tasks obtained thanks to 133 different participants from the three universities. We use three metrics to assess the developers’ comprehension of the source code - (1) the duration to complete each task; (2) their percentage of correct answers; and, (3) the NASA task load index for their effort. Conclusions - We report that, although single occurrences of Blob or Spaghetti code anti-patterns have little effect on code comprehension, two occurrences of either Blob or Spaghetti Code significantly increases the developers’ time spent in their tasks, reduce their percentage of correct answers, and increase their effort. Hence, we recommend that developers act on both anti-patterns, which should be refactored out of the source code whenever possible. We also recommend further studies on combinations of anti-patterns rather than on single anti-patterns one at a time.

# Summary. An optional shortened abstract.
summary: Although single occurrences of Blob or Spaghetti code anti-patterns have little effect on code comprehension, two occurrences of either Blob or Spaghetti Code significantly increases the developers’ time spent in their tasks, reduce their percentage of correct answers, and increase their effort. Hence, we recommend that developers act on both anti-patterns, which should be refactored out of the source code whenever possible.

tags:
- Anti-patterns
- Blob
- Spaghetti Code
- Program comprehension
- Java
featured: true

links:
- name: ScienceDirect
  url: http://www.sciencedirect.com/science/article/pii/S0950584920300288

url_pdf: /publication/2020politowski/2020Politowski.pdf
#url_code: 'https://github.com/swarmdebugging'
#url_dataset: 'https://doi.org/10.5281/zenodo.3601564'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: 'https://www.youtube.com/watch?v=llyPqKwUdlc'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- anti-pattern
---
