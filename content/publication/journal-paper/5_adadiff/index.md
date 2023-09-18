---
title: 'Adaptive diffusion priors for accelerated MRI reconstruction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Alper Güngör
  - Salman UH Dar
  - Şaban Öztürk
  - Yılmaz Korkmaz
  - admin
  - Gökberk Elmas
  - Muzaffer Özbey
  - Tolga Çukur

date: '2023-06-20T00:00:00Z'
doi: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Medical Image Analysis*
publication_short: In *MEDIA*

abstract: "Deep MRI reconstruction is commonly performed with conditional models that de-alias undersampled acquisitions to recover images consistent with fully-sampled data. Since conditional models are trained with knowledge of the imaging operator, they can show poor generalization across variable operators. Unconditional models instead learn generative image priors decoupled from the operator to improve reliability against domain shifts related to the imaging operator. Recent diffusion models are particularly promising given their high sample fidelity. Nevertheless, inference with a static image prior can perform suboptimally. Here we propose the first adaptive diffusion prior for MRI reconstruction, AdaDiff, to improve performance and reliability against domain shifts. AdaDiff leverages an efficient diffusion prior trained via adversarial mapping over large reverse diffusion steps. A two-phase reconstruction is executed following training: a rapid-diffusion phase that produces an initial reconstruction with the trained prior, and an adaptation phase that further refines the result by updating the prior to minimize data-consistency loss. Demonstrations on multi-contrast brain MRI clearly indicate that AdaDiff outperforms competing conditional and unconditional methods under domain shifts, and achieves superior or on par within-domain performance."


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.sciencedirect.com/science/article/pii/S1361841523001329'
url_code: 'https://github.com/icon-lab/AdaDiff'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](featured.jpg)'
  focal_point: ''
  preview_only: false

---
