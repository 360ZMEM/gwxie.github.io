---
title: "FISHER: An Efficient Sim2Sim Training Framework Dedicated in Multi-AUV Target Tracking via Learning from Demonstrations"
authors:
- admin
- Jingzehua Xu
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
date: "2024-03-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract:  Multiple autonomous underwater vehicles (AUVs) target tracking problem is a significant challenge for AUV swarm control, which is crucial to the growth of the marine industry. To emphasize the great adaptability while tackling the limitations of reinforcement learning (RL) methods in Multi-AUV target tracking tasks, we propose an efficient twostage learning from demonstrations (LfD) training framework, FISHER, based on few-shot expert demonstration, featuring imitation learning (IL) and offline reinforcement learning (ORL). In the first stage, we develop a sample-efficient algorithm, multi-agent independent discriminator actor-critic (MAIDAC), to facilitate the imitation of expert policy and the generation of offline datasets. In the second stage, based on decision transformer (DT), the reward function-indepentent algorithm, multi-agent independent generalized decision transformer (MAIGDT) is utilized for further policy improvement. Simultaneously, we propose a simulation to simulation (sim2sim) method to facilitate the generation of expert trajectories, which is compatible with traditional methods like artificial potential field (APF). Through comparative experiments, we verify the improvement of the proposed MAIDAC and MAIGDT algorithms, and we further demonstrate the strong performance and practicality of the proposed FISHER by full target tracking simulation processes.
summary: In submission


tags:
- Source Themes
featured: True

links:
- name: Project webpage
  url: https://sites.google.com/view/fisher2024
url_pdf: ''
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
url_video: 'https://www.youtube.com/watch?v=W1qwWOZ4-wk'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'The schematic diagram of our proposed training framework FISHER.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
