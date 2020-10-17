---
title: "Object-level Attention for Aesthetic Rating Distribution Prediction"
authors:
- Jingwen Hou
- Sheng Yang
- Weisi Lin
date: ""
doi: "10.1145/3394171.3413695"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: 2020 ACM International Conference on Multimedia
publication_short: ACMMM 2020

abstract: We study the problem of image aesthetic assessment (IAA) and aim to automatically predict the image aesthetic quality in the form of discrete distribution, which is particularly important in IAA due to its nature of having possibly higher diversification of agreement for aesthetics. Previous works show the effectiveness of utilizing object-agnostic attention mechanisms to selectively concentrate on more contributive regions for IAA, e.g., attention is learned to weight pixels of input images when inferring aesthetic values. However, as suggested by some neuropsychology studies, the basic units of human attention are visual objects, i.e., the trace of human attention follows a series of objects. This inspires us to predict contributions of different regions at object level for better aesthetics evaluation. With our framework, region-of-interests (RoIs) are proposed by an object detector, and each RoI is associated with a regional feature vector. Then the contribution of each regional feature to the aesthetics prediction is adaptively determined. To the best of our knowledge, this is the first work modeling object-level attention for IAA and experimental results confirm the superiority of our framework over previous relevant methods.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
- name: Custom Link
  url: http://example.org
url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: '#'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

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
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

