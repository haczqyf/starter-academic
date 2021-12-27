---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Geometric graphs from data to aid classification tasks with graph convolutional networks"
authors: [Yifan Qian, Paul Expert, Pietro Panzarasa, Mauricio Barahona]
date: 2021-04-09
doi: "10.1016/j.patter.2021.100237"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-26T18:01:15Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Patterns*"
publication_short: ""

abstract: "Traditional classification tasks learn to assign samples to given classes based solely on sample features. This paradigm is evolving to include other sources of information, such as known relations between samples. Here, we show that, even if additional relational information is not available in the dataset, one can improve classification by constructing geometric graphs from the features themselves, and using them within a Graph Convolutional Network. The improvement in classification accuracy is maximized by graphs that capture
sample similarity with relatively low edge density. We show that such feature-derived graphs increase the
alignment of the data to the ground truth while improving class separation. We also demonstrate that the
graphs can be made more efficient using spectral sparsification, which reduces the number of edges while
still improving classification performance. We illustrate our findings using synthetic and real-world datasets
from various scientific domains."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
#links:
#- name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: files/qian2021geometric.pdf
url_code: https://github.com/haczqyf/ggc
url_dataset: https://github.com/haczqyf/ggc/tree/master/ggc/data
url_poster:
url_project:
url_slides:
url_source: https://www.cell.com/patterns/fulltext/S2666-3899(21)00057-X
url_video: https://www.youtube.com/watch?v=_H71bbNKO3Q

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
