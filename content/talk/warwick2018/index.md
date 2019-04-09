+++
title = "Pseudo-Marginal Hamiltonian Monte Carlo with Efficient Importance Sampling"
date = 2017-01-01T00:00:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2018-07-11T17:30:00
time_end = 2018-07-11T19:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

# Abstract and optional shortened version.
abstract = "The joint posterior of latent variables and parameters in Bayesian hierarchical models often has a strong nonlinear dependence structure, thus making it a challenging target for standard Markov-chain Monte-Carlo methods. Pseudo-marginal methods aim at effectively exploring such target distributions, by marginalizing the latent variables using Monte-Carlo integration and directly targeting the marginal posterior of the parameters. We follow this approach and propose a generic pseudo-marginal algorithm for efficiently simulating from the posterior of the parameters. It combines efficient importance sampling, for accurately marginalizing the latent variables, with the recently developed pseudo-marginal Hamiltonian Monte Carlo approach. We illustrate our algorithm in applications to dynamic state space models, where it shows a very high simulation efficiency even in challenging scenarios with complex dependence structures."
abstract_short = "An example talk using Academic's Markdown slides feature."

# Name of event and optional event URL.
event = "CRISM Summer School on Computational Statistics 2018"
event_url = "https://warwick.ac.uk/fac/sci/statistics/crism/workshops/lms2018/"

# Location of event.
location = "University of Warwick"

# Is this a selected talk? (true/false)
selected = true

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
url_slides = "talk/warwick2018/poster.pdf"
url_video = ""
url_code = ""

# Does the content use math formatting?
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Right"
+++

Poster presentation.