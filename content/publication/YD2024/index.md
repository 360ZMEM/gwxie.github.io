---
title: 'Multi-AUV Assisted Seamless Underwater Target Tracking Relying on Deep Learning and Reinforcement Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yimian Ding
  - Jingzehua Xu
  - admin
  - Ziyuan Wang
  - Yongming Zeng
  - Gang Li

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-02-02T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-02-02T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE World Congress on Computational Intelligence (WCCI)*
# publication_short: In *ICW*

abstract: Since seamless tracking of the underwater target is crucial for various underwater applications, we propose a fusion algorithm combining deep learning and reinforcement learning for multi-autonomous underwater vehicles (AUVs) to seamlessly track the underwater target. The framework of our proposed fusion algorithm consists of two stages. In the first stage, we propose an underwater target localization method based on convolutional neural network (CNN) that relies on shaft-rate electric fields, in which the data collected by underwater sensors is utilized to train CNN to achieve accurate target localization. In the second stage, we innovatively propose a multi-agent soft actor-critic (MASAC) reinforcement learning algorithm based on centralized training with decentralized execution, in which appropriate reward functions are designed to encourage multiple AUVs to cooperate in seamlessly tracking the target in unknown environments while avoiding obstacles. Simulation results show that the proposed fusion algorithm has excellent performance, while the real-time target localization accuracy is 97.8%, and AUVs can carry out seamlessly cooperative tracking of the target in unknown environment.


tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

links:
- name: News coverage (Chinese)
  url: 'http://oc.zju.edu.cn/2024/0329/c29862a2896096/page.htm'
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
  caption: 'The framework of our proposed fusion algorithm for seamless tracking of the underwater target.'
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
