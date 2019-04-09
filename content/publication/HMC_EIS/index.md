+++
title = "Pseudo-Marginal Hamiltonian Monte Carlo with Efficient Importance Sampling"
date = 2018-12-19
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
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = "arXiv"
publication_short = "arXiv"

# Abstract and optional shortened version.
abstract = "The joint posterior of latent variables and parameters in Bayesian hierarchical models often has a strong nonlinear dependence structure, thus making it a challenging target for standard Markov-chain Monte-Carlo methods. Pseudo-marginal methods aim at effectively exploring such target distributions, by marginalizing the latent variables using Monte-Carlo integration and directly targeting the marginal posterior of the parameters. We follow this approach and propose a generic pseudo-marginal algorithm for efficiently simulating from the posterior of the parameters. It combines efficient importance sampling, for accurately marginalizing the latent variables, with the recently developed pseudo-marginal Hamiltonian Monte Carlo approach. We illustrate our algorithm in applications to dynamic state space models, where it shows a very high simulation efficiency even in challenging scenarios with complex dependence structures."
abstract_short = "Combining pseudo-marginal Hamiltonian Monte Carlo with Efficient Importance Sampling, to sample from target distributions with strong nonlinear dependencies."

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
url_pdf = ""
url_preprint = "https://arxiv.org/pdf/1812.07929.pdf"
url_code = ""
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
