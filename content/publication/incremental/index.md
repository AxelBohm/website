---
title: "An incremental mirror descent subgradient algorithm with random sweeping and proximal step"
authors:
- Radu Bot
- admin
author_notes:
- "Equal contribution"
- "Equal contribution"
doi: "https://doi.org/10.1080/02331934.2018.1482491"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Optimization, 68*(1)"
publication_short: ""

abstract: We investigate the convergence properties of incremental mirror descenttype subgradient algorithms for minimizing the sum of convex functions.In each step, we only evaluate the subgradient of a single component func-tion and \textit{mirror} it back to the feasible domain, which makes iterations verycheap to compute. The analysis is made for a randomized selection of thecomponent functions, which yields the deterministic algorithm as a specialcase. Under supplementary differentiability assumptions on the functionwhich induces the mirror map, we are also able to deal with the presenceof another term in the objective function, which is evaluated via a proximaltype step. In both cases, we derive convergence rates of $O(1/\sqrt$k$)$ in expectation for the $k$-th best objective function value and illustrate our theoretical findings by numerical experiments in positron emission tomography and machine learning.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.tandfonline.com/doi/pdf/10.1080/02331934.2018.1482491?needAccess=true
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
slides: example
---

[comment]: # (Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).)
