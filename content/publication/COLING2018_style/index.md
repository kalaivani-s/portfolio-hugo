---
title: "What represents 'style' in authorship attribution?"
authors:
- Kalaivani Sundararajan
- Damon Woodard
date: "2018-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 27th International Conference on Computational Linguistics*
publication_short: In *COLING*

abstract: Authorship attribution typically uses all information representing both content and style whereas attribution based only on stylistic aspects may be robust in cross-domain settings. This paper analyzes different linguistic aspects that may help represent style. Specifically, we study the role of syntax and lexical words (nouns, verbs, adjectives and adverbs) in representing style. We use a purely syntactic language model to study the significance of sentence structures in both single-domain and cross-domain attribution, ie cross-topic and cross-genre attribution. We show that syntax may be helpful for cross-genre attribution while cross-topic attribution and single-domain may benefit from additional lexical information. Further, pure syntactic models may not be effective by themselves and need to be used in combination with other robust models. To study the role of word choice, we perform attribution by masking all words or specific topic words corresponding to nouns, verbs, adjectives and adverbs. Using a single-domain dataset, IMDB1M reviews, we demonstrate the heavy influence of common nouns and proper nouns in attribution, thereby highlighting topic interference. Using cross-domain Guardian10 dataset, we show that some common nouns, verbs, adjectives and adverbs may help with stylometric attribution as demonstrated by masking topic words corresponding to these parts-of-speech. As expected, it was observed that proper nouns are heavily influenced by content and cross-domain attribution will benefit from completely masking them.

# Summary. An optional shortened abstract.
summary: This paper looks at suitable feature representations for cross-domain stylometric attribution.

tags:
- Stylometry
- Cross-domain
- NLP
featured: false

#links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://www.aclweb.org/anthology/C18-1238.pdf
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/Oaqk7qqNh_c)'
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

