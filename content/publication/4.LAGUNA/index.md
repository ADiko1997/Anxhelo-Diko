---
title: "S-GEAR: Semantically Guided Representation Learning for Action Anticipation (ECCV2024)"
authors:
- admin
- Antonino Furnari
- Luigi Cinque
- Giovanni Maria Farinella

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

abstract: Unsupervised domain adaptation remains a critical challenge in enabling the knowledge transfer of models across unseen domains. Existing methods struggle to balance the need for domain-invariant representations with preserving domain-specific features, which is often due to alignment approaches that impose the projection of samples with similar semantics close in the latent space despite their drastic domain differences. We introduce LAGUNA - LAnguage Guided UNsupervised Adaptation with structured spaces, a novel approach that shifts the focus from aligning representations in absolute coordinates to aligning the relative positioning of equivalent concepts in latent spaces. LAGUNA defines a domain-agnostic structure upon the semantic/geometric relationships between class labels in language space and guides adaptation, ensuring that the organization of samples in visual space reflects reference inter-class relationships while preserving domain-specific characteristics. We empirically demonstrate LAGUNA's superiority in domain adaptation tasks across four diverse images and video datasets. Remarkably, LAGUNA surpasses previous works in 18 different adaptation scenarios across four diverse image and video datasets with average accuracy improvements of +3.32% on DomainNet, +5.75% in GeoPlaces, +4.77% on GeoImnet, and +1.94% mean class accuracy improvement on EgoExo4D.


tags:
- Source Themes
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://arxiv.org/abs/2411.15557'
url_code: 'https://arxiv.org/abs/2411.15557'
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