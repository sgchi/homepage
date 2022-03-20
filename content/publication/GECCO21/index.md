---
title: "Evolutionary meta reinforcement learning for portfolio optimization"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Myoung Hoon Ha
- admin
- Sangyeop Lee
- Yujin Cha
- Byung-Ro Moon

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2021-07-01T00:00:00Z"
doi: "10.1145/3449639.3459386"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the Genetic and Evolutionary Computation Conference*
publication_short: In *GECCO*

abstract: Portfolio optimization is a control problem whose objective is to find the optimal strategy for the process of selecting the proportions of assets that can provide the maximum return. Conventional approaches formulate the problem as a single Markov decision process and apply reinforcement learning methods to provide solutions. However, it is well known that financial markets involve non-stationary processes, leading to violations of this assumption in these methods. In this work, we reformulate the portfolio optimization problem to deal with the non-stationary nature of financial markets. In our approach, we divide a long-term process into multiple short-term processes to adapt to context changes and consider the portfolio optimization problem as a multitask control problem. Thereafter, we propose an evolutionary meta reinforcement learning approach to search for an initial policy that can quickly adapt to the upcoming target tasks. We model the policies as convolutional networks that can score the match of the patterns in market data charts. Finally, we test our approach using real-world cryptographic currency data and show that it adapts well to the changes in the market and leads to better profitability.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

#url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3449639.3459386'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

In *Proceedings of the Genetic and Evolutionary Computation Conference* (GECCO), 2021

<!--Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).-->
