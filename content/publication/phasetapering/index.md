---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Removing Phase Transitions from Gibbs Measures"
authors: ["Ian E. Fellows", "admin"]
date: 2017-04-20
doi: #"10.1093/jssam/smx018"

# Schedule page publish date (NOT publication's date).
#publishDate: 2022-01-10T21:28:45Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 20th International Conference on Artificial Intelligence and Statistics (AISTATS)"
publication_short: ""

abstract: "Gibbs measures are a fundamental class of distributions for the
analysis of high dimensional data. Phase transitions, which are also known as
degeneracy in the network science literature, are an emergent property of these
models that well describe many physical systems.  However, the reach of the
Gibbs measure is now far outside the realm of physical systems, and in many of
these domains multiphase behavior is a nuisance. This nuisance often makes
distribution fitting impossible due to failure of the MCMC sampler, and even
when an MLE fit is possible, if the solution is near a phase transition point,
the plausibility of the fit can be highly questionable. We introduce a
modification to the Gibbs distribution that reduces the effects of phase
transitions, and with properly chosen hyper-parameters, provably removes all
multiphase behavior. We show that this new distribution is just as easy to fit
via MCMCMLE as the Gibbs measure, and provide examples in the Ising model from
statistical physics and ERGMs from network science."

# Summary. An optional shortened abstract.
summary: ""

tags: ["respondent-driven sampling", "link-tracing", "not missing at random", "network sampling", "social network", "hard-to-reach population", "snowball sampling"]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: http://proceedings.mlr.press/v54/fellows17a/fellows17a.pdf
url_code: #https://github.com/qingyuanzhao/bets.covid19
url_dataset: #https://github.com/qingyuanzhao/bets.covid19
url_poster:
url_project:
url_slides: #talk/yale-biostats-2020/slides.pdf
url_source: http://proceedings.mlr.press/v54/fellows17a.html
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
projects: ["sampling"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
