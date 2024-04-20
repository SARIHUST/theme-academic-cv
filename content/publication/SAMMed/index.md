---
title: 'Leveraging SAM for Single-Source Domain Generalization in Medical Image Segmentation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Huaize Ye
  - Yi Xia
  - Xueyan Zhang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-01-04T00:00:00Z'
doi: '
https://doi.org/10.48550/arXiv.2401.02076
'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-04T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['preprint']

# Publication name and optional abbreviated publication name.
publication: In *Arxiv*
publication_short: In *Arxiv*

abstract: Domain Generalization (DG) aims to reduce domain shifts between domains to achieve promising performance on the unseen target domain, which has been widely practiced in medical image segmentation. Single-source domain generalization (SDG) is the most challenging setting that trains on only one source domain. Although existing methods have made considerable progress on SDG of medical image segmentation, the performances are still far from the applicable standards when faced with a relatively large domain shift. In this paper, we leverage the Segment Anything Model (SAM) to SDG to greatly improve the ability of generalization. Specifically, we introduce a parallel framework, the source images are sent into the SAM module and normal segmentation module respectively. To reduce the calculation resources, we apply a merging strategy before sending images to the SAM module. We extract the bounding boxes from the segmentation module and send the refined version as prompts to the SAM module. We evaluate our model on a classic DG dataset and achieve competitive results compared to other state-of-the-art DG methods. Furthermore, We conducted a series of ablation experiments to prove the effectiveness of the proposed method. The code is publicly available at https://github.com/SARIHUST/SAMMed.

# Summary. An optional shortened abstract.
summary: To leverage SAM's flexibility and domain knowledge, we propose a novel fine-tuning paradigm for single-source domain generalization of medical image segmentation.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://arxiv.org/pdf/2401.02076.pdf
url_code: https://github.com/SARIHUST/SAMMed

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
