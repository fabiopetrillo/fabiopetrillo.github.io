---
title: "On semantic detection of cloud API (anti)patterns"
authors:
- Hayet Brabra
- Achraf Mtibaa
- Fabio Petrillo
- Philippe Merle
- Layth Sliman
- Naouel Moha
- Walid Gaaloul
- Yann-Gaël Guéhéneuc
- Boualem Benatallah
- Faïez Gargouri

date: "2019-03-01T00:00:00Z"
doi: "10.1016/j.infsof.2018.10.012"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-03-01T00:00:00Z"
 
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Information and Software Technology
publication_short: IST

abstract: Context - Open standards are urgently needed for enabling software interoperability in Cloud Computing. Open Cloud Computing Interface (OCCI) provides a set of best design principles to create interoperable REST management APIs. Although OCCI is the only standard addressing the management of any kind of cloud resources, it does not support a range of best principles related to REST design. This often worsens REST API quality by decreasing their understandability and reusability. Objective - We aim at assisting cloud developers to enhance their REST management APIs by providing a compliance evaluation of OCCI and REST best principles and a recommendation support to comply with these principles. Method - First, we leverage patterns and anti-patterns to drive respectively the good and poor practices of OCCI and REST best principles. Then, we propose a semantic-based approach for defining and detecting REST and OCCI (anti)patterns and providing a set of correction recommendations to comply with both REST and OCCI best principles. We validated this approach by applying it on cloud REST APIs and evaluating its accuracy, usefulness and extensibility. Results - We found that our approach accurately detects OCCI and REST(anti)patterns and provides useful recommendations. According to the compliance results, we reveal that there is no widespread adoption of OCCI principles in existing APIs. In contrast, these APIs have reached an acceptable level of maturity regarding REST principles. Conclusion - Our approach provides an effective and extensible technique for defining and detecting OCCI and REST (anti)patterns in Cloud REST APIs. Cloud software developers can benefit from our approach and defined principles to accurately evaluate their APIs from OCCI and REST perspectives. This contributes in designing interoperable, understandable, and reusable Cloud management APIs. Thank to the compliance analysis and the recommendation support, we also contribute to improving these APIs, which make them more straightforward.

# Summary. An optional shortened abstract.
summary: We aim at assisting cloud developers to enhance their REST management APIs by providing a compliance evaluation of OCCI and REST best principles and a recommendation support to comply with these principles.

tags:
- Cloud computing
- REST
- OCCI
- Pattern
- Anti-pattern
- Analysis
- Specification
- Detection
- Ontology
featured: true

links:
- name: ScienceDirect
  url: https://www.sciencedirect.com/science/article/abs/pii/S095058491830226X

url_pdf: /publication/2019Brabra/2019Brabra.pdf
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
  caption: 'Overview of the Swarm Debugging approach'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- cloud computing
---