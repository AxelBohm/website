---
title: "Two steps at a time -- taking GAN training in stride with Tseng's method"
authors:
- admin
- Michael Sedlmayer
- Ernö R. Csetnek
- Radu Bot
date: "2020-06-16T00:00:00Z"
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
  Motivated by the training of Generative Adversarial Networks (GANs), we study methods for solving minimax problems with additional nonsmooth regularizers.
  We do so by employing \emph{monotone operator} theory, in particular the \emph{Forward-Backward-Forward (FBF)} method, which avoids the known issue of limit cycling by correcting each update by a second gradient evaluation.
  Furthermore, we propose a seemingly new scheme which recycles old gradients to mitigate the additional computational cost.
  In doing so we rediscover a known method, related to \emph{Optimistic Gradient Descent Ascent (OGDA)}.
  For both schemes we prove novel convergence rates for convex-concave minimax problems via a unifying approach. The derived error bounds are in terms of the gap function for the ergodic iterates.
  For the deterministic and the stochastic problem we show a convergence rate of $\mathcal{O}(\nicefrac{1}{k})$ and $\mathcal{O}(\nicefrac{1}{\sqrt{k}})$, respectively.
  We complement our theoretical results with empirical improvements in the training of Wasserstein GANs on the CIFAR10 dataset.


# Summary. An optional shortened abstract.
summary: We propose the use of Tseng's method in the training of GANs.

tags:
- minimax
- saddle point
- SGD
- convex

featured: false

links:
url_pdf: https://arxiv.org/abs/2006.09033
url_code: 'https://github.com/AxelBohm/FBF-GAN'
url_dataset: '#'

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
