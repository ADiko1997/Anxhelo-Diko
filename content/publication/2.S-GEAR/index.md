---
title: "S-GEAR: Semantically Guided Representation Learning for Action Anticipation (ECCV2024)"
authors:
- admin
- Danilo Avola
- Bardh Prenkaj
- Federico Fontana
- Luigi Cinque

date: "2024-07-01"
doi: ""


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Action anticipation is the task of forecasting future activity from a partially observed sequence of events. However, this task is exposed to intrinsic future uncertainty and the difficulty of reasoning upon interconnected actions. Unlike previous works that focus on extrapolating better visual and temporal information, we concentrate on learning action representations that are aware of their semantic interconnectivity based on prototypical action patterns and contextual co-occurrences. To this end, we propose the novel Semantically Guided Representation Learning (S-GEAR) framework. S-GEAR learns visual action prototypes and leverages language models to structure their relationship, inducing semanticity. To gather insights on S-GEAR's effectiveness, we test it on four action anticipation benchmarks, obtaining improved results compared to previous works -- +3.5, +2.7, and +3.5 absolute points on Top-1 Accuracy on Epic-Kitchen 55, EGTEA Gaze+ and 50 Salads, respectively, and +0.8 on Top-5 Recall on Epic-Kitchens 100. We further observe that S-GEAR effectively transfers the geometric associations between actions from language to visual prototypes. Finally, S-GEAR opens new research frontiers in anticipation tasks by demonstrating the intricate impact of action semantic interconnectivity. We will release our code online upon acceptance.


tags:
- Source Themes
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'cooming soon'
url_code: 'https://github.com/ADiko1997/S-GEAR/tree/main'
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