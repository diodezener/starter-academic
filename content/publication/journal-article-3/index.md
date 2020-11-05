---
title: "Emulating Synchrophasor Frequency Measurements with Transient Stability Simulation"
authors:
- admin
- J. E. Tate
author_notes:
- "1"
- "2"
date: "2020-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "* submitted to IEEE Transactions on Power Systems"
publication_short: ""

abstract: In transient stability simulators such as PSS/E, the bus frequency is estimated using a window of (positive-sequence) phasor angle measurements. A digital filter is often used to account for the filtering effect in actual measurement devices and to eliminate sudden changes during frequency computations .Although transient stability simulators label the filtered angle derivative as the "frequency", the frequency provided by such programs does not match actual measurements reported by phasor measurement units (PMUs), which makes it difficult to gauge the validity of studies (e.g., wide-area event detection and control applications) that are based on such simulations. In this paper, we implement a frequency computation method directly using positive phasor angles provided by simulators. The proposed method is tested on two systems extensively and validated against the measurements of an actual PMU. The improved frequency measurements closely match PMU responses. Cross-validation results also suggest the method may be used for other systems without conducting full time-domain simulations.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: files/emulating.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


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
