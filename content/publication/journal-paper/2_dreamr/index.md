---
title: 'DreaMR: Diffusion-driven Counterfactual Explanation for Functional MRI'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tolga Çukur

date: '2023-07-18T00:00:00Z'
doi: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: under review, *IEEE Transactions on Medical Imaging*
publication_short: under review, *IEEE TMI*

abstract: Deep learning analyses have offered sensitivity leaps in detection of cognitive states from functional MRI (fMRI) measurements across the brain. Yet, as deep models perform hierarchical nonlinear transformations on their input, interpreting the association between brain responses and cognitive states is challenging. Among common explanation approaches for deep fMRI classifiers, attribution methods show poor specificity and perturbation methods show limited plausibility. While counterfactual generation promises to address these limitations, previous methods use variational or adversarial priors that yield suboptimal sample fidelity. Here, we introduce the first diffusion-driven counterfactual method, DreaMR, to enable fMRI interpretation with high specificity, plausibility and fidelity. DreaMR performs diffusion-based resampling of an input fMRI sample to alter the decision of a downstream classifier, and then computes the minimal difference between the original and counterfactual samples for explanation. Unlike conventional diffusion methods, DreaMR leverages a novel fractional multi-phase-distilled diffusion prior to improve sampling efficiency without compromising fidelity, and it employs a transformer architecture to account for long-range spatiotemporal context in fMRI scans. Comprehensive experiments on neuroimaging datasets demonstrate the superior specificity, fidelity and efficiency of DreaMR in sample generation over state-of-the-art counterfactual methods for fMRI interpretation.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2307.09547'
url_code: 'https://github.com/icon-lab/DreaMR'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](featured.png)'
  focal_point: ''
  preview_only: false

---
