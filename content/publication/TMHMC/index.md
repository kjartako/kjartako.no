+++
title = "Importance Sampling-based Transport Map Hamiltonian Monte Carlo for Bayesian Hierarchical Models"
date = 2021-05-03
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Kjartan Kloster Osmundsen", "Tore Selland Kleppe", "Roman Liesenfeld"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*Journal of Computational and Graphical Statistics*, 1-32"
publication_short = "*Journal of Computational and Graphical Statistics*, 1-32"

# Abstract and optional shortened version.
abstract = "We propose an importance sampling (IS)-based transport map Hamiltonian Monte Carlo procedure for performing a Bayesian analysis in nonlinear high-dimensional hierarchical models. Using IS techniques to construct a transport map, the proposed method transforms the typically highly complex posterior distribution of a hierarchical model such that it can be easily sampled using standard Hamiltonian Monte Carlo. In contrast to standard applications of high-dimensional IS, our approach does not require IS distributions with high fidelity, which makes it computationally very cheap. Moreover, it is less prone to the notorious problem of IS that the variance of IS weights can become infinite. We illustrate our algorithm with applications to challenging dynamic state-space models, where it exhibits very high simulation efficiency compared to relevant benchmarks, even for variants of the proposed method implemented using a few dozen lines of code in the Stan statistical software. The paper is accompanied by supplementary material containing further details, and the computer code is available at https://github.com/kjartako/TMHMC."
#abstract_short = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://www.tandfonline.com/doi/full/10.1080/10618600.2021.1923519"
url_preprint = ""
url_code = "https://github.com/kjartako/TMHMC"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
