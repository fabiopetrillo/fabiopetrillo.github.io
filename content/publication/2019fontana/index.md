---
title: "Visualizing Sequences of Debugging Sessions Using Swarm Debugging"
authors:
- Eduardo A. Fontana
- admin

date: "2019-05-25T00:00:00Z"
doi: "10.1109/ICPC.2019.00030"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-05-25T00:00:00Z"
 
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: 27th International Conference on Program Comprehension (ICPC)
publication_short: IEEE/ACM ICPC 2019

abstract: In Software Engineering, one of the most important activities is debugging. Debugging is a set of techniques to detect, locate, and correct faults in a computer program. Modern Integrated Development Environments (IDEs), such as Eclipse or Visual Studio, provide infrastructure to support interactive debugging, during which a developer explores the source code of the system under development or maintenance. Although IDEs encourage developers to work collaboratively, debugging is still an individual activity. Furthermore, interactive debugging activity is limited by IDE debugging features that do not store previous debugging sessions. This condition forces developers to repeat debugging execution sessions to review the debugging information. In this paper, using the concept of Swarm Debugging, we present the Sequence Debugging Session View (SDV) tool. The primary goal is to capture the debugging information from a developer IDE (as Visual Studio) and store it. Then, the tool enables developers to retrieve the data in 3D interactive visualization and understand software behavior through the analysis and sharing of debugging session data. The main contribution of the tool is to assist on program comprehension and to reduce effort during software maintenance. To validate the solution, we performed two usage studies in real situations at a software house. The feedback from the evaluation of the tool suggests that the team could be helped on the software arrangement.

# Summary. An optional shortened abstract.
summary: In this paper, using the concept of Swarm Debugging, we present the Sequence Debugging Session View (SDV) tool. The primary goal is to capture the debugging information from a developer IDE (as Visual Studio) and store it.

tags:
- Swarm Debugging
- Debugging
- interactive visualization
- Software Visualization
- Information visualization
featured: false

links:
#- name: arXiv
#  url: https://arxiv.org/abs/1912.08861
- name: IEEE
  url: https://ieeexplore.ieee.org/document/8813303
- name: ACM
  url: https://dl.acm.org/doi/pdf/10.1109/ICPC.2019.00030

url_pdf: /publication/2019fontana/2019Fontana.pdf
url_code: 'https://github.com/eduardoafontana'
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
url_video: 'https://youtu.be/3HiRGIxdczs'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Visualization of debugging sessions'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- swarm debugging
---