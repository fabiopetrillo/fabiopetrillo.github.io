---
title: "Serverless architecture efficiency: an exploratory study"
authors:
- Samuel Lavoie
- Anthony Garant
- admin
date: "2019-01-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-01-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: arXiv preprint arXiv:1901.03984
publication_short: In *arXiv preprint*

abstract: Cloud service provider propose services to insensitive customers to use their platform. Different services can achieve the same result at different cost. In this paper, we study the efficiency of a serverless architecture for running highly parallelizable tasks to compare theses services in order to find the most efficient in term of performance and cost. More precisely, we look at the compute time and at the cost per task for a given task. The tasks studied is the count of the occurrence of a given word in a corpus. We compare the serverless architecture to the Apache Spark map reduce technique commonly used for this type of task. Using AWS Lambda for the serverless architecture and Amazon EMR for the Apache Spark map reduce, with similar compute power, we show that the serverless technique achieve comparable performance in term of compute time and cost. We observed that the lambda function is a great approach for real time computing, while EMR is preferable for task that require long compute time.  

# Summary. An optional shortened abstract.
summary: We study the efficiency of a serverless architecture for running highly parallelizable tasks to compare theses services in order to find the most efficient in term of performance and cost.

tags:
- Serverless
- Software Architecture
- Cloud computing
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/1901.03984
url_pdf: https://arxiv.org/pdf/1901.03984


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Papers selection methodology and results'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- Cloud Computing
---



