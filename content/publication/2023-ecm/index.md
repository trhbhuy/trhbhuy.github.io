---
title: "Real-time energy scheduling for home energy management systems with an energy storage system and electric vehicle based on a supervised-learning-based strategy"
authors:
- admin
- Huy Truong Dinh
- Dieu Ngoc Vo
- Daehee Kim
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-09-15T00:00:00Z"
doi: "https://doi.org/10.1016/j.enconman.2023.117340"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-06T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Energy Conversion and Management, 292*"
# publication: "*Energy Conversion and Management, 292*(1)"
publication_short: ""

abstract: With rising energy costs and concerns about environmental sustainability, there is a growing need to deploy Home Energy Management Systems (HEMS) that can efficiently manage household energy consumption. This paper proposes a new supervised-learning-based strategy for optimal energy scheduling of an HEMS that considers the integration of energy storage systems (ESS) and electric vehicles (EVs). The proposed supervised-learning-based HEMS framework aims to optimize the energy costs of households by forecasting the energy demand and simultaneously scheduling the charging and discharging operations of ESS and EV. From the scenarios extracted from historical data, the HEMS optimization problem is solved using a mixed-integer linear programming (MILP) solver to collect the datasets on the optimal actions of the ESS and EV. Accordingly, a supervised learning method is used to learn the optimal actions of the MILP solver using deep neural networks (DNNs). Well-trained DNNs act as decision-making tools that are subsequently applied to predict near-optimal actions for ESS and EV based on real-time data. The effectiveness of the proposed method is demonstrated through simulation results and compared with deep reinforcement learning-based and forecasting-based methods. The results show that the proposed method can significantly reduce energy costs and improve the efficiency of ESS and EV operations. Overall, the proposed supervised-learning-based HEMS offers a practical and effective solution for residential energy management.

# Summary. An optional shortened abstract.
summary: This paper presents a supervised-learning-based Home Energy Management System (HEMS) that optimizes household energy costs by forecasting demand and scheduling energy storage and electric vehicle operations, significantly improving efficiency.

tags:
- Energy Management
- HEMS
- Imitation Learning
- Supervised Learning
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: https://github.com/trhbhuy/supervised-learning-home-energy-management
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Supervised-learning-based HEMS strategy: [**Elsevier**](https://ars.els-cdn.com/content/image/1-s2.0-S0196890423006866-gr2_lrg.jpg)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
