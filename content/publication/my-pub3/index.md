---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Scalable domain decomposition solvers for stochastic PDEs in high performance computing"
authors: ["admin", "Mohammad Khalil", "Chris Pettit", "Dominique Poirel", "Abhijit Sarkar"]
date: 2020-01-20T14:08:00-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-01-20T14:08:00-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Stochastic spectral finite element models of practical engineering systems may involve solutions of linear systems or linearized systems for non-linear problems with billions of unknowns. For stochastic modeling, it is therefore essential to design robust, parallel and scalable algorithms that can efficiently utilize high-performance computing to tackle such large-scale systems. Domain decomposition based iterative solvers can handle such systems. Although these algorithms exhibit excellent scalabilities, significant algorithmic and implementational challenges exist to extend them to solve extreme-scale stochastic systems using emerging computing platforms. Intrusive polynomial chaos expansion based domain decomposition algorithms are extended here to concurrently handle high resolution in both spatial and stochastic domains using an in-house implementation. Sparse iterative solvers with efficient preconditioners are employed to solve the resulting global and subdomain level local systems through multi-level iterative solvers. Parallel sparse matrix–vector operations are used to reduce the floating-point operations and memory requirements. Numerical and parallel scalabilities of these algorithms are presented for the diffusion equation having spatially varying diffusion coefficient modeled by a non-Gaussian stochastic process. Scalability of the solvers with respect to the number of random variables is also investigated."

# Summary. An optional shortened abstract.
summary: "A multi-level solver is developed for domain decomposition (DD) of Stochastic PDEs. It extends the capabilities of DD algorithms to handle many random variables. The solver utilizes numerous sparse objects and routines from PETSc, FEniCS and MPI."

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

url_pdf: https://www.osti.gov/pages/servlets/purl/1399891
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
