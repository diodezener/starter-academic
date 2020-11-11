---
title: "External System Generator Outage Localization Based on Tie-Line Synchrophasor Measurements"
authors:
- admin
- J. E. Tate
author_notes:
- "1"
- "2"
date: "2020-03-01T00:00:00Z"
doi: "10.1109/TPWRS.2019.2942257"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "* IEEE Transactions on Power Systems (Volume: 35, Issue: 2, March 2020)"
publication_short: ""

abstract: An identification algorithm is proposed for generator outages in external systems given tie-line flow measurements and pre-outage linear sensitivity factors. The problem is challenging due to limited information available to operators in interconnected systems. To overcome the underdetermined nature of the problem (the number of tie-line measurements is smaller than the number of generators), a clustering method based on pivoted QR decomposition is implemented so that the outage location can be identified to the area of origination. Two test systems, the 68-bus New England system and the 500-bus synthetic system, were used for validation. The results demonstrate that with limited knowledge of the external system, the algorithm is able to identify the correct generator cluster in all cases. Another advantage of the proposed algorithm is its high efficiency, which enables detection within sub-milliseconds. In addition, an estimation of the cluster injection change is also provided by the algorithm.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- generator outages
- wide-area power systems
- identification
- linear sensitivity factors
- PMUs
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: files/08843926.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'slides/20PESGM0225.pdf'
url_source: ''
url_video: 'media/20PESGM0225.mp4'


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