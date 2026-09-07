---
title: "Finite-Sample Validity Is Not Robustness: A Precinct-Level Geospatial Simulation Case Study"
authors:
- me
- Tianxiang Lu
date: "2026-08-07T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-08-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Prior work on LLM conformity largely measures discrete answer flips under verifiable labels. Open-ended revisions require a different measurement strategy because answer quality is graded, latent, and judged imperfectly. We introduce an experimental protocol implemented across a pooled main peer-condition corpus and separately constructed decomposition corpora, allowing us to separate ordinary re-answering, candidate-content exposure, a bundled peer-presentation residual, and directional judge sensitivity to visible peer context. Across four open-weight generators and three benchmarks, all-wrong peer input produces the lowest-quality revisions in every generator-dataset cell. Blind and informed ratings of identical answers also differ by evaluator; one judge shifts toward the peer-endorsed position, two shift away, one is approximately neutral, and GPT-4o and GPT-5.4-mini audits are likewise non-neutral. Finally, an anchor audit shows that terse correct anchors can be misread often enough to destabilize the latent scale unless calibration is checked explicitly. These results support four conclusions; these conclusions are that flip rates are insufficient as a complete measure of open-ended conformity, wrong peers harm open-ended revision, evaluators are not neutral, and anchor calibration is necessary.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Large Language Models
- Multi-Agent Systems 

featured: true

hugoblox:
  ids:
    arxiv: 2608.04463

links:
- type: preprint
  provider: arxiv
  id: 2608.04463
- type: code
  url: https://github.com/HugoBlox/kit
- type: slides
  url: https://www.slideshare.net/
- type: dataset
  url: "#"
- type: poster
  url: "#"
- type: source
  url: "#"
- type: video
  url: https://youtube.com
- type: custom
  label: Custom Link
  url: http://example.org

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "aag_2026"` references `content/slides/aag_2026/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

