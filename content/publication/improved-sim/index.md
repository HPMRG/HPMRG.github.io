---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Improving simulation-based algorithms for fitting ERGMs"
authors: ["Ruth M. Hummel", "David R. Hunter", "admin"]
date: 2012-03-06
doi: "10.1080/10618600.2012.679224"

# Schedule page publish date (NOT publication's date).
#publishDate: 2022-01-10T21:28:45Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Computational and Graphical Statistics"
publication_short: ""

abstract: "Markov chain Monte Carlo methods can be used to approximate the intractable normalizing constants that arise in likelihood
calculations for many exponential-family random graph models for networks. However, in practice, the resulting approximations degrade as
parameter values move away from the value used to define the Markov chain, even in cases where the chain produces perfectly efficient samples.
We introduce a new approximation method along with a novel method of moving toward a maximum likelihood estimator (MLE) from an arbitrary
starting parameter value in a series of steps based on alternating between the canonical exponential-family parameterization and the
mean-value parameterization. This technique enables us to find an approximate MLE in many cases where this was previously not possible. We
illustrate these methods on a model for a transcriptional regulation network for E. coli, an example where previous attempts to approximate an
MLE had failed, and a model for a well-known social network dataset involving friendships among workers in a tailor shop. These methods are
implemented in the publicly available ergm package for R, and computer code to duplicate the results of this article is included in the online
supplementary materials."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Exponential-family random graph model", "Markov chain Monte Carlo", "Maximum likelihood estimation", "Mean value parameterization"]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.tandfonline.com/doi/pdf/10.1080/10618600.2012.679224
url_code: #https://github.com/qingyuanzhao/bets.covid19
url_dataset: #https://github.com/qingyuanzhao/bets.covid19
url_poster:
url_project:
url_slides: #talk/yale-biostats-2020/slides.pdf
url_source:
url_video: #https://publichealth.yale.edu/biostat/media-player/5158/

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
projects: ["network-modeling"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
