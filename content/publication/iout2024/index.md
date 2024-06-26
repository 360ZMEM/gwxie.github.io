---
title: "Environment and Energy-Aware AUV-Assisted Data Collection for the Internet of Underwater Things"
authors:
  - Zekai Zhang
  - Jingzehua Xu
  - admin
  - Jingjing Wang
  - Zhu Han
  - Yong Ren
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
date: "2024-03-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-02T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "In *IEEE Internet of Things Journal*, early access"
# publication_short: ""

abstract: Considering the wide-area distribution and limited transmission power of sensing devices in the Internet of Underwater Things (IoUT), employing autonomous underwater vehicles (AUVs) to collect data is considered a promising solution. While most existing AUV-assisted data collection schemes primarily focus on enhancing data collection throughput and identifying the shortest path, they often overlook the influence of the underwater environment on AUV and the timeliness of data collection. In this paper, we design a multi-AUV-assisted data collection system, in which AUVs select their own target devices to collect data according to the data upload urgencies of IoUT devices. Considering the disturbance of turbulent ocean environment and the limited energy of AUV, we propose an environment and energy-aware AUV-assisted data collection scheme. This scheme aims to conduct path planning for multiple AUVs based on perceived environmental information, including turbulent fields and device statuses. The primary goals are to maximize the sum data collection rate and total data throughput, minimize AUV energy consumption, reduce the average data overflow times. To solve this high-dimensional NP-hard problem, we first model the problem as a Markov decision process, and propose a multi-agent independent soft actor-critic to solve it. Extensive simulations validate the effectiveness and adaptability of our approach.



tags:
- Source Themes
featured: false

# links:
url_pdf: https://ieeexplore.ieee.org/document/10516675/
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Illustration of multi-AUV assisted data collection system.'
  focal_point: ""
  preview_only: false


---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
