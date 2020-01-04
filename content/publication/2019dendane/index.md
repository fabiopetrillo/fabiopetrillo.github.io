---
title: "Quality model for evaluating and choosing a stream processing framework architecture"
authors:
- Youness Dendane
- Fabio Petrillo
- Hamid Mcheick 
- Souhail Ben-Ali

date: "2019-11-03T00:00:00Z"
#doi: "10.1109/VISSOFT.2019.00013"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-11-03T00:00:00Z"
 
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: 16th ACS/IEEE International Conference on Computer Systems and Applications (AICCSA 2019)
publication_short: IEEE AICCSA 2019

abstract: Today, we have to deal with many data (Big data) and we need to make decisions by choosing an architectural framework to analyze these data coming from different area. Due to this, it becomes problematic when we want to process these data, and even more, when it is continuous data. When you want to process some data, you have to first receive it, store it, and then query it. This is what we call Batch Processing. It works well when you process big amount of data, but it finds its limits when you want to get fast (real-time) processing results, such as financial trades, sensors, user session activity, etc. The solution to this problem is stream processing. Stream processing approach consists of data arriving record by record, and rather than storing it, the processing is done as the data arrive. In this paper, we propose an assessment quality model to evaluate and choose stream processing frameworks. We describe briefly different architectural frameworks such as Spark Streaming, Storm, Flink and Samza that address the stream processing. Using our quality model, we present a decision tree to support engineers to choose a framework following the quality aspects. Finally, we evaluate our model doing a case study to Twitter and Netflix streaming; model that will serve as well for engineers, as for future framework designers.

# Summary. An optional shortened abstract.
summary: We propose an assessment quality model to evaluate and choose stream processing frameworks.

tags:
- stream processing
- software arquitecture
- software engineering
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/1901.09062
#- name: IEEE
#  url: https://ieeexplore.ieee.org/document/8900972

url_pdf: /publication/2019dendane/2019Dandane.pdf
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
  caption: 'Stream processing framework decision tree'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- software_architecture
---



