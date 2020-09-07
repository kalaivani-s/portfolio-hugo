---
title: "Head pose estimation in the wild using approximate view manifolds"
authors:
- Kalaivani Sundararajan
- Damon Woodard
date: "2015-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2015-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition Workshops
publication_short: In *CVPR*

abstract: In this paper, we present a head pose estimation method for unconstrained images using feature-based manifold embedding. The main challenge of manifold embedding methods is to learn a similarity kernel that is reflective of variations only due to head pose and ignore other sources of variation. To address this challenge, we have used the feature correspondences of identity-invariant Geometric Blur features to learn a similarity kernel. To speed up the computation of the similarity kernel, we have used spatial pyramidal matching to approximate feature correspondences and random subsampling of training samples to approximate graph neighborhood. In addition to these approximations, we have used the Nystrom approximation to embed out-of-sample test images in an efficient manner. Using these approximations, an approximate view manifold was learned for 14000 images in the Annotated Facial Landmarks in the Wild (AFLW) dataset. With the learned manifold, head pose estimation was performed on four in-the-wild face datasets-AFLW (remaining 7000 images), AFW, McGill and YouTube Faces. The Approximate View Manifold training achieves a 7X speedup compared to the non-approximated Learning-manifold-in-the-wild approach. Further, pose estimation using the proposed approach shows significant improvement in accuracy and reduced Mean Angular Error (MAE) compared to other methods on the challenging AFLW (7041 images), McGill (6833 images) and YouTube Faces (22534 images) datasets.

# Summary. An optional shortened abstract.
summary: Approximation techniques to speed up head pose estimation using manifold embedding approach.

tags:
- Head pose estimation, Manifold embedding, Spatial pyramidal matching
featured: false

links:
url_pdf: https://www.cv-foundation.org/openaccess/content_cvpr_workshops_2015/W08/papers/Sundararajan_Head_Pose_Estimation_2015_CVPR_paper.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/vtZSP-g-mXE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
