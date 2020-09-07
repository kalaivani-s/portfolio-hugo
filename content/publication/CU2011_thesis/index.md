---
title: "Unified point-edgelet feature tracking"
authors:
- Kalaivani Sundararajan
date: "2011-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2011-05-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: In *MS Thesis - Clemson University*
publication_short: In *MS Thesis*

abstract: Feature tracking algorithms have conventionally tracked "corner" features or windows with high spatial frequency content. However, this conventional point feature representation of scenes would be inappropriate for poorly textured image sequences like indoor image sequences. To overcome this problem, we propose a feature tracking algorithm which tracks point features and edgelets simultaneously. Edgelets are straight line approximations of intensity edges in an image. Hence, a combination of point features and edgelets provides a better representation of untextured sequences with the point features and edgelets complementing each other. We show that this property results in more robust tracking. Tracking edgelets is challenging due to the inherent aperture problem. This thesis proposes an optical flow-based tracking method to track both point features and edgelets in a combined fashion. The aperture problem of the edgelets is overcome using Horn-Schunck regularisation to penalize flow vector deviations from those of the neighboring features. This method uses a translational motion model for tracking individual features and hence only the change in displacement of the point features and edgelets is computed. The point features are detected using the Shi-Tomasi method. The edgelets are detected using the Canny edge map and Douglas-Peucker polyline approximation algorithm. It is assumed that motion will be constant in a neighborhood around the point feature and for all edgels in an edgelet. The point features and edgelets are tracked by minimizing an energy function consisting of the optical flow constraint and sum of negative gradient magnitude of edgels. Thus the edgelets which are typically attracted to the nearby intensity edges will be guided by the optical flow constraint equation and by the motion of the neighboring features. We have also implemented a pyramidal implementation of our algorithm with the uppermost pyramidal level representing the original image and the lower pyramidal levels consisting of the downsampled images. The unified feature tracking method utilizes a pyramidal implementation which respects the scale at which the features are visible. Hence, the motion vector computation at lower pyramidal levels is reliable and improves the tracking robustness. Moreover, the average flow vector due to the neighboring features is computed by fitting an affine motion model to the neighboring features. The neighboring features are weighted based on their distance from the feature and the pyramidal level at which they are visible.

# Summary. An optional shortened abstract.
summary: This thesis explores a sparse feature tracking approach using point features and edgelets for use in indoor scenes with poor texture.

tags:
- Feature tracking
- Optical flow
- Computer Vision
featured: false

#links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://tigerprints.clemson.edu/cgi/viewcontent.cgi?article=2122&context=all_theses
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
  caption: 'Unified feature tracking in indoor scenario'
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

