---
title: 'BolT: Fused window transformers for fMRI time series analysis'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hasan A. Bedel
  - Irmak Sıvgın
  - Onat Dalmaz
  - Salman UH Dar
  - Tolga Çukur

date: '2023-08-01T00:00:00Z'
doi: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Medical Image Analysis*
publication_short: In *MEDIA*

abstract: Deep-learning models have enabled performance leaps in analysis of high-dimensional functional MRI (fMRI) data. Yet, many previous methods are suboptimally sensitive for contextual representations across diverse time scales. Here, we present BolT, a blood-oxygen-level-dependent transformer model, for analyzing multi-variate fMRI time series. BolT leverages a cascade of transformer encoders equipped with a novel fused window attention mechanism. Encoding is performed on temporally-overlapped windows within the time series to capture local representations. To integrate information temporally, cross-window attention is computed between base tokens in each window and fringe tokens from neighboring windows. To gradually transition from local to global representations, the extent of window overlap and thereby number of fringe tokens are progressively increased across the cascade. Finally, a novel cross-window regularization is employed to align high-level classification features across the time series. Comprehensive experiments on large-scale public datasets demonstrate the superior performance of BolT against state-of-the-art methods. Furthermore, explanatory analyses to identify landmark time points and regions that contribute most significantly to model decisions corroborate prominent neuroscientific findings in the literature.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.sciencedirect.com/science/article/pii/S1361841523001019'
url_code: 'https://github.com/icon-lab/BolT'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](featured.jpg)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
