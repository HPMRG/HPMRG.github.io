---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Practical Network Modeling via Tapered Exponential-family Random Graph Models"
authors: ["Bart Blackburn", "admin"]
date: 2022-08-24
doi: "10.1080/10618600.2022.2116444"

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

abstract: "Exponential-family Random Graph Models (ERGMs) have long been at the forefront of the analysis of relational data. The
exponential-family form allows complex network dependencies to be represented. Models in this class are interpretable, flexible and have a
strong theoretical foundation. The availability of powerful user-friendly open-source software allows broad accessibility and use. However, ERGMs sometimes suffer from a serious condition known as near-degeneracy, in which the model exhibits unrealistic probabilistic behavior or a severe lack-of-fit to real network data.
<p>
Recently, Fellows and Handcock (2017) proposed a new model class, the Tapered ERGM, which circumvents the issue of near-degeneracy while maintaining the
desirable features of ERGMs. However, the question of how to determine the proper amount of tapering needed for any model was heretofore left
unanswered. This paper develops a new methodology for how to determine the necessary level of tapering and as such provides a new approach to
inference for the Tapered ERGM class. Noting that a Tapered ERGM can always be made non-degenerate, we offer data-driven approaches for
determining the amount of tapering necessary. The mean-value parameter estimates are unaffected by tapering, and we show that the natural
parameter estimates are numerically weakly varying by the level of tapering. We then apply the Tapered ERGM to two published networks to
demonstrate its effectiveness in cases where typical ERGMs fail and present the case for Tapered ERGMs replacing ERGMs entirely."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Exponential-family Random Graph Model", "Social Network Analysis", "Degeneracy", "Goodness-of-Fit"]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: publication/tapering/JCGS-21-292-accepted-version.pdf
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
projects: ["networks"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
