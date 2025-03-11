---
title: "ReWind: Understanding Long Videos with Instructed Learnable Memory (CVPR2025)"
authors:
- admin
- Tinghuai Wang
- Wassim Swaileh
- Shiyan Sun
- Ioannis Patras

date: "2024-12-01"
doi: ""


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Vision-Language Models (VLMs) are crucial for applications requiring integrated understanding textual and visual information. However, existing VLMs struggle with long videos due to computational inefficiency, memory limitations, and difficulties in maintaining coherent understanding across extended sequences. To address these challenges, we introduce ReWind, a novel memory-based VLM designed for efficient long video understanding while preserving temporal fidelity. ReWind operates in a two-stage framework. In the first stage, ReWind maintains a dynamic learnable memory module with a novel \textbf{read-perceive-write} cycle that stores and updates instruction-relevant visual information as the video unfolds. This module utilizes learnable queries and cross-attentions between memory contents and the input stream, ensuring low memory requirements by scaling linearly with the number of tokens. In the second stage, we propose an adaptive frame selection mechanism guided by the memory content to identify instruction-relevant key moments. It enriches the memory representations with detailed spatial information by selecting a few high-resolution frames, which are then combined with the memory contents and fed into a Large Language Model (LLM) to generate the final answer. We empirically demonstrate ReWind's superior performance in visual question answering (VQA) and temporal grounding tasks, surpassing previous methods on long video benchmarks. Notably, ReWind achieves a +13\% score gain and a +12\% accuracy improvement on the MovieChat-1K VQA dataset and an +8\% mIoU increase on Charades-STA for temporal grounding.


tags:
- Source Themes
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://arxiv.org/abs/2411.15556'
url_code: 'https://arxiv.org/abs/2411.15556'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---