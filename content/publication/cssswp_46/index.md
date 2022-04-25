---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Model-Based Clustering for Social Networks"
authors: ["admin", "Adrian E. Raftery", "Jeremy M. Tantrum"]
date: 2005-04-27
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
publication_short: "CSSS Working Paper #46"

abstract: "Network models are widely used to represent relations among interacting units or actors.
Network data often exhibit transitivity, meaning that two actors that have ties to a third
actor are more likely to be tied than actors that do not, homophily by attributes of the
actors or dyads, and clustering. Interest often focuses on  nding clusters of actors or ties,
and the number of groups in the data is typically unknown. We propose a new model, the
Latent Position Cluster Model (LPCM), under which the probability of a tie between two
actors depends on the distance between them in an unobserved Euclidean social space,
and the actors' locations in the latent social space arise from a mixture of distributions, each
one corresponding to a cluster. We propose two estimation methods: a two-stage maximum
likelihood method, and a Bayesian MCMC method; the former is quicker and simpler, but the
latter performs better. We also propose a Bayesian way of determining the number of clusters
present using approximate conditional Bayes factors. It models transitivity, homophily by
attributes and clustering simultaneously, and does not require the number of clusters to be
known. The model makes it easy to simulate realistic networks with clustering, potentially
useful as inputs to models of more complex systems of which the network is part, such as
epidemic models of infectious disease. We apply the model to two networks of social relations."

# Summary. An optional shortened abstract.
summary: ""

tags: ["social networks", "latent position models", "methodology"]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://csss.uw.edu/files/working-papers/2005/wp46.pdf
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
projects: ["methodology"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
