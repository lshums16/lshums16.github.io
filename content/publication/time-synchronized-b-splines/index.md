---
title: "Time-Synchronized B-spline Path Planning for Multi-Agent UAV Systems"
authors:
- Landon Shumway
- Randal W. Beard
date: "2025-04-09T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "International Conference on Unmanned Aircraft Systems"
# publication_short: "ICUAS"

abstract: Most UAV path planning methods assume that speed is constant or controllable within certain constraints. However, some applications require UAVs to follow predefined speed profiles. This paper proposes a novel offline path planning algorithm for multi-agent UAV systems with fixed speed profiles that facilitates scheduled arrivals at desired final states in $\mathbb{R}^2$-space using uniform B-splines. The B-splines are parameterized by a path variable to decouple the path geometry from the speed profile, and a path extension algorithm is introduced for timely arrival. We present the path planning methods and demonstrate their effectiveness through Monte Carlo simulations of a formation control example. Results show that the proposed algorithm consistently ensures simultaneous arrival within 0.2 seconds in all cases, with an average deviation of only 0.07 seconds, regardless of initial conditions. This approach offers an effective solution for coordinated UAV missions with fixed speed profiles.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Path planning
- Multi-agent systems
- B-splines
featured: true

# links:
# - name: ""
#   url: ""
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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

{{% callout note %}}
This paper has been accepted but not yet published at the time of writing.
{{% /callout %}}
