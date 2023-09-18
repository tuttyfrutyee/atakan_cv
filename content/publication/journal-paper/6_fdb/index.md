---
title: 'Learning Fourier-Constrained Diffusion Bridges for MRI Reconstruction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Muhammda U. Mirza
  - Onat Dalmaz
  - admin
  - Gökberk Elmas
  - Yılmaz Korkmaz
  - Alper Güngör
  - Salman UH Dar
  - Tolga Çukur

date: '2023-08-02T00:00:00Z'
doi: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: under review, *Medical Image Analysis*
publication_short: under review, *MEDIA*

abstract: Recent years have witnessed a surge in deep generative models for accelerated MRI reconstruction. Diffusion priors in particular have gained traction with their superior representational fidelity and diversity. Instead of the target transformation from undersampled to fully-sampled data, common diffusion priors are trained to learn a multi-step transformation from Gaussian noise onto fully-sampled data. During inference, data-fidelity projections are injected in between reverse diffusion steps to reach a compromise solution within the span of both the diffusion prior and the imaging operator. Unfortunately, suboptimal solutions can arise as the normality assumption of the diffusion prior causes divergence between learned and target transformations. To address this limitation, here we introduce the first diffusion bridge for accelerated MRI reconstruction. The proposed Fourier-constrained diffusion bridge (FDB) leverages a generalized process to transform between undersampled and fully-sampled data via random noise addition and random frequency removal as degradation operators. Unlike common diffusion priors that use an asymptotic endpoint based on Gaussian noise, FDB captures a transformation between finite endpoints where the initial endpoint is based on moderate degradation of fully-sampled data. Demonstrations on brain MRI indicate that FDB outperforms state-of-the-art reconstruction methods including conventional diffusion priors.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2308.01096'
url_code: 'https://github.com/icon-lab/FDB'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](featured.png)'
  focal_point: ''
  preview_only: false

---
