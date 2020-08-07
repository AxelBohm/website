---
title: "Alternating proximal-gradient steps for (stochastic) nonconvex-concave minimax problems"
authors:
- admin
- Radu Bot
date: "2020-03-17T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: 
  We study minimization of a structured objective function, being the
  sum of a smooth function and a composition of a weakly convex
  function with a linear operator. Applications include image
  reconstruction problems with regularizers that introduce less bias
  than the standard convex regularizers. We develop a variable
  smoothing algorithm, based on the Moreau envelope with a decreasing
  sequence of smoothing parameters, and prove a complexity of
  $\mathcal{O}(\epsilon^{-3})$ to achieve an $\epsilon$-approximate solution. This
  bound interpolates between the $\O(\epsilon^{-2})$ bound for the smooth
  case and the $\mathcal{O}(\epsilon^{-4})$ bound for the subgradient method. Our
  complexity bound is in line with other works that deal with
  structured nonsmoothness of weakly convex functions.

# Summary. An optional shortened abstract.
summary: We study the composition of a weakly convex function with a linear operator and prove a novel convergence rate of $\mathcal{O}(\epsilon^{-3})$ for an algorithm based on the Moreau envelope

tags:
- smoothing
- Moreau envelope
- weakly convex

featured: true

links:
- name: Steve
  url: http://pages.cs.wisc.edu/~swright/
url_pdf: https://arxiv.org/pdf/2003.07612.pdf

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

[comment]: # (Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).)