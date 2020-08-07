---
title: "Alternating proximal-gradient steps for (stochastic) nonconvex-concave minimax problems"
authors:
- Radu Bot
- admin
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2019-04-07T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Minimax problems of the form $\min_x \max_y \Psi(x,y)$ have attracted increased interest largely due to advances in machine learning, in particular generative adversarial networks. These are typically trained using variants of stochastic gradient descent for the two players. Although convex-concave problems are well understood with many efficient solution methods to choose from, theoretical guarantees outside of this setting are sometimes lacking even for the simplest algorithms. In particular, this is the case for alternating gradient descent ascent, where the two agents take turns updating their strategies. To partially close this gap in the literature we prove a novel global convergence rate for the stochastic version of this method for finding a critical point of $g(\cdot) := \max_y \Psi(\cdot,y)$ in a setting which is not convex-concave.

# Summary. An optional shortened abstract.
summary: We prove a novel convergence rate of two-time-scale _alternating_ gradient descent ascent for nonconvex-concave minimax problems.

tags:
- minimax
- saddle point
- weakly convex
- GAN
- SGD

tags:
- Source Themes
featured: false

links:
url_pdf: https://arxiv.org/pdf/2007.13605.pdf

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
