---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Quantifying the alignment of graph and features in deep learning"
authors: [Yifan Qian, Paul Expert, Tom Rieu, Pietro Panzarasa, Mauricio Barahona]
date: 2021-01-11
doi: "10.1109/TNNLS.2020.3043196"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-26T17:43:20Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Neural Networks and Learning Systems*"
publication_short: ""

abstract: "We show that the classification performance of Graph Convolutional Networks is related to the alignment between features, graph and ground truth, which we quantify using a subspace alignment measure corresponding to the Frobenius norm of the matrix of pairwise chordal distances between three subspaces associated with features, graph and ground truth. The proposed measure is based on the principal angles between subspaces and has both spectral and geometrical interpretations. We showcase the relationship between the subspace alignment measure and the classification performance through the study of limiting cases of Graph Convolutional Networks as well as systematic randomizations of both features and graph structure applied to a constructive example and several examples of citation networks of different origin. The analysis also reveals the relative importance of the graph and features for classification purposes."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter


url_pdf: files/qian2021quantifying.pdf
url_code: https://github.com/haczqyf/gcn-data-alignment
url_dataset: https://github.com/haczqyf/gcn-data-alignment/tree/master/alignment/data
url_poster:
url_project:
url_slides:
url_source: https://ieeexplore.ieee.org/document/9319542
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Center"
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
