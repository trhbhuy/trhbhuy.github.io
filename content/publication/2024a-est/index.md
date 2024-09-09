---
title: "Real-time power scheduling for an isolated microgrid with renewable energy and energy storage system via a supervised-learning-based strategy"
authors:
- admin
- Tien-Dat Le
- Pham Van Phu
- Seongkeun Park
- Daehee Kim
date: "2024-05-30T00:00:00Z"
doi: "https://doi.org/10.1016/j.est.2024.111506"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-04-12T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Energy Storage, 88*"
publication_short: ""

abstract: |
  In the future of decentralized energy systems, isolated microgrids integrated with renewable energy and energy storage systems (ESS) have emerged as critical solutions for areas beyond conventional grid connectivity. Optimal power scheduling is essential for the efficient operation, cost efficiency, and stability of isolated microgrids. Therefore, this study proposes a new supervised learning (SL) strategy for real-time optimal power scheduling of an isolated microgrid. The proposed approach is three-fold: First, a deterministic mixed-integer linear programming (MILP) model is established for the optimal power scheduling problem of an isolated microgrid to minimize operational costs. By harnessing historical data, this optimization model is solved by a dedicated MILP solver to obtain an expert dataset of optimal decisions in the isolated microgrids. Second, an SL strategy is deployed to learn and mimic optimal ESS charging/discharging decisions by training a dense residual neural network (ResNetD) on the obtained expert dataset. Finally, the well-trained ResNetD model is applied to provide near-optimal power scheduling decisions based on real-time information. The performance of the proposed method is validated using a comprehensive set of test scenarios and compared with the base case, myopic policy, and other well-known deep reinforcement learning. The results reveal that the SL method reduces operating costs by 5.95 % and the output of the diesel engine generator by 12.67 % compared to the base case. Moreover, the SL method provides high-quality solutions that closely approximate the ideal results with an average performance gap of 0.37 %. Therefore, the proposed method demonstrates its robust adaptability to the real-time conditions of an isolated microgrid environment.

# Summary. An optional shortened abstract.
summary: This study proposes a supervised-learning-based strategy for real-time power scheduling in isolated microgrids with renewable energy and energy storage systems, showing significant cost reductions and operational efficiency improvements.

tags:
- Isolated microgrid
- Energy storage system
- Power scheduling
- Renewable energy
- Supervised learning
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: https://github.com/trhbhuy/resnetd-isolated-microgrid-scheduling
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Schematic diagram of the proposed isolated microgrid: [**Elsevier**](https://ars.els-cdn.com/content/image/1-s2.0-S0306261924012303-gr2_lrg.jpg)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- isolated-microgrid-project

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