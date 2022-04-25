---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "New specifications for exponential random graph models"
authors: ["Tom A.B. Snijders", "Philippa E. Pattison", "Garry L. Robins", "admin"]
date: 2004-04-23
doi: #"http://www.stern.nyu.edu/~jsimonof/Casebook"

# Schedule page publish date (NOT publication's date).
#publishDate: 2022-01-10T21:28:45Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Center for Statistics and Social Sciences"
publication_short: "CSSS Working Paper #42"

abstract: "The most promising class of statistical models for expressing structural properties of social
networks is the class of Exponential Random Graph Models (ERGMs), also known as $p^*$ 
models. The strong point of these models is that they can represent structural tendencies,
such as transitivity, that define complicated dependence patterns not easily modeled by more
basic probability models. Recently, MCMC algorithms have been developed which produce
approximate Maximum Likelihood estimators. Applying these models in their traditional
specification to observed network data often has led to problems, however, which can be
traced back to the fact that important parts of the parameter space correspond to nearly
degenerate distributions, which may lead to convergence problems and a poor fit to empirical
data.
<p>
This paper proposes new specifications of the exponential random graph model. These
specifications represent structural properties such as transitivity and heterogeneity of degrees
by more complicated graph statistics than the traditional star and triangle counts. Three
kinds of statistic are proposed: geometrically weighted degree distributions, alternating ktriangles,
and alternating independent two-paths. Examples are presented both of modeling
graphs and digraphs, in which the new specifications lead to much better results than the
earlier existing specifications of the ERGM. It is concluded that the new specifications increase
the range and applicability of the ERGM as a tool for the statistical analysis of social
networks."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Statistical modeling", "Social networks", "Graphs", "Transitivity", "Clustering", "Maximum likelihood", "MCMC, p* model"]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://csss.uw.edu/files/working-papers/2004/wp42.pdf
url_code: #http://www.stern.nyu.edu/~jsimonof/Casebook
url_dataset: #http://www.stern.nyu.edu/~jsimonof/Casebook
url_poster:
url_project: #"http://www.stern.nyu.edu/~jsimonof/Casebook"
url_slides: #http://www.stat.ucla.edu/~handcock/csde01.pdf
url_source: #http://www.stern.nyu.edu/~jsimonof/Casebook
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
projects: ["networks"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
