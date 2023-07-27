---
title: "MS-Faster R-CNN: Multi-stream backbone for improved Faster R-CNN object detection and aerial tracking from UAV images"
authors:
- Danilo Avola
- Luigi Cinque
- admin
- Alessio Fagioli
- Gian Luca Foresti
- Alessio Mecca
- Daniele Pannone
- Claudio Piciarelli

date: "2021-04-25"
doi: ""


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Tracking objects across multiple video frames is a challenging task due to several difficult issues such as occlusions, background clutter, lighting as well as object and camera view-point variations, which directly affect the object detection. These aspects are even more emphasized when analyzing unmanned aerial vehicles (UAV) based images, where the vehicle movement can also impact the image quality. A common strategy employed to address these issues is to analyze the input images at different scales to obtain as much information as possible to correctly detect and track the objects across video sequences. Following this rationale, in this paper, we introduce a simple yet effective novel multi-stream (MS) architecture, where different kernel sizes are applied to each stream to simulate a multi-scale image analysis. The proposed architecture is then used as backbone for the well-known Faster-R-CNN pipeline, defining a MS-Faster R-CNN object detector that consistently detects objects in video sequences. Subsequently, this detector is jointly used with the Simple Online and Real-time Tracking with a Deep Association Metric (Deep SORT) algorithm to achieve real-time tracking capabilities on UAV images. To assess the presented architecture, extensive experiments were performed on the UMCD, UAVDT, UAV20L, and UAV123 datasets. The presented pipeline achieved state-of-the-art performance, confirming that the proposed multi-stream method can correctly emulate the robust multi-scale image analysis paradigm.


tags:
- Source Themes
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://www.mdpi.com/2072-4292/13/9/1670
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
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


{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
