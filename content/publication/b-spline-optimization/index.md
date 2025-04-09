---
title: "Non-Uniform B-spline Trajectory Optimization using Control Point Representation Transformations"
authors:
- David Christensen
- Landon Shumway
- Randal W. Beard
- Timothy W. McLain
date: "2025-04-09T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "American Control Conference"
# publication_short: "ACC"

abstract: Online trajectory generation for unmanned aerial vehicles has attracted increased interest for a variety of autonomous applications. This paper explores the use of non-uniform B-splines to produce improved time-optimal trajectories in comparison to contemporary work that uses uniform B-splines. This paper introduces the non-uniform B-spline matrix form and the transformation of non-uniform B-spline control points to other parametric representations such as MINVO and B\'ezier control points. Conversion between control point representations allows the optimization to take advantage of the piecewise continuity of B-splines, as well as the tighter convex bounding properties of MINVO and B\'ezier curve representations. The results show that non-uniform B-spline trajectories significantly outperform uniform B-splines trajectories in time optimality and path length. However, computational performance is degraded when optimizing for non-uniform B-splines, thus requiring computational improvements for online use.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Path planning
- B-spline Optimization
- Non-uniform B-splines
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
