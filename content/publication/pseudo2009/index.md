---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Framework for the Comparison of Maximum Pseudo Likelihood and Maximum Likelihood Estimation of Exponential Family Random Graph Models"
authors: ["Marijtje van Duijn", "Krista J. Gile", "admin"]
date: 2009-03-01
doi: "10.1016/j.socnet.2008.10.003"

# Schedule page publish date (NOT publication's date).
#publishDate: 2022-01-10T21:28:45Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Social Networks"
publication_short: ""

abstract: "The statistical modeling of social network data is difficult due to the complex dependence structure of the tie variables.
Statistical exponential families of distributions provide a flexible way to model such dependence. They enable the statistical characteristics
of the network to be encapsulated within an exponential family random graph (ERG) model. For a long time, however, likelihood-based estimation
was only feasible for ERG models assuming dyad independence. For more realistic and complex models inference has been based on the
pseudo-likelihood. Recent advances in computational methods have made likelihood-based inference practical, and comparison of the different
estimators possible.
<p>
In this paper, we present methodology to enable estimators of ERG model parameters to be compared. We use this methodology to compare the bias,
standard errors, coverage rates and efficiency of maximum likelihood and maximum pseudo-likelihood estimators. We also propose an improved
pseudo-likelihood estimation method aimed at reducing bias. The comparison is performed using simulated social network data based on two
versions of an empirically realistic network model, the first representing Lazega’s law firm data and the second a modified version with
increased transitivity. The framework considers estimation of both the natural and the mean-value parameters.
<p>
The results clearly show the superiority of the likelihood-based estimators over those based on pseudo-likelihood, with the bias-reduced
pseudo-likelihood out-performing the general pseudo-likelihood. The use of the mean-value parameterization provides insight into the
differences between the estimators and when these differences will matter in practice."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Networks", "statnet", "Dyad dependence", "Mean-value parameterization", "Markov Chain Monte Carlo"]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://escholarship.org/uc/item/8mf9v56f
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
