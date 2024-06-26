---
title: 'Advanced Framework for Underwater Node Repair via Multi-AUV Based on Multi-Agent Offline Reinforcement Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yimian Ding
  - Jingzehua Xu
  - admin
  - Gang Li
  - Jingjing Wang
  - Yong Ren

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-06-04T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-06-04T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *OCEANS 2024 - Halifax*
# publication_short: In *ICW*

abstract: The Internet of Underwater Things (IoUT) has gained attention for improving ocean exploration and monitoring.    However, challenges like environmental damage and power limitations cause node failures, leading to routing issues, communication delays, and potentially, system failure. Current research focuses on energy-efficient routing protocols, but in densely deployed networks, this can lead to packet collisions and the need for retransmissions. Unfortunately, existing methods can hardly address increasing sensor node energy storage or repairing damaged nodes.  In this study, we develop an advanced framework for underwater node repair via autonomous underwater vehicles (AUVs) based on multi-agent offline reinforcement learning (RL). The framework optimizes the trajectories of multi-AUV, considering practical constraints and turbulence in underwater environments. The aim is to efficiently train multi-AUV for underwater node repair, based on external conditions and device status, to enhance repair rates while minimizing energy consumption and maximizing hazardous areas avoidance, further ensuring continuous operation of the IoUT network. The problem is modeled as a partially observable Markov decision process (POMDP) due to its high-dimensional NPhard nature, and is addressed with our proposed multi-agent independent conservative Q-learning (MAICQL) algorithm. Extensive simulations not only demonstrate the effectiveness in solving the underwater node repair task, but also showcase the superior performance and robustness of MAICQL.


tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

links:
- name: "PDF coming soon"
  url: ""
# url_pdf: ''
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Multi-AUV assisted underwater nodes repair scenario.'
  focal_point: ''
  preview_only: false


---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
