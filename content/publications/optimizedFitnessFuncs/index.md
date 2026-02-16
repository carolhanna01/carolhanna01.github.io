---
title: "Optimised fitness functions for automated improvement of software's execution time"

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Dimitrios Stamatios Bouras
  - Carol Hanna
  - Justyna Petke

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# date: '2023-12-10'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-11-16'


# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In Symposium on Search-Based Software Engineering
# publication_short: In International symposium on search based software engineering

abstract: Precise measurement of software execution time is challenging due to environmental variability and measurement overheads, an issue critical for search-based software improvement systems that evaluate thousands of variants. While precise measurements offer precise fitness measures, they often introduce a significant time overhead. To understand which measures are most effective as fitness functions in search-based software optimisation, we conducted an empirical study of 21 approximates of execution time. These included hardware-level counters from perf, RAPL energy, and a custom measure based on weighted instruction cycles. To improve reliability, we evaluated each fitness function up to five times, using medians to reduce noise. We integrated the 13 most promising measures into a search-based software optimisation framework called MAGPIE. We evaluated these fitness functions plus Time, already present in MAGPIE, on 7 benchmarks using both code-level and parameter-level mutations. To assess generalizability, we tested the best performing measures with the parameter tuning tool ParamILS and analyzed how tool and search strategy affect outcomes. Our results show that perf’s cycles measure yields the best overall performance, outperforming Time by 5.1%. Sampling three times balances reliability and exploration. Energy and the weight-based measure excel in specific scenarios, with weights being the best for parameter optimization on MAGPIE, but are better suited to longer searches due to their overhead. We highlight a trade-off- low-overhead measures like Time work well for short runs, while robust measures such as cycles and weights benefit longer ones.

tags:
  - Runtime
  - Genetic Improvement

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  # ids:
  #   doi: 10.5555/123456

# Custom links
links:
  - type: paper
    label: Paper
    url: "https://solar.cs.ucl.ac.uk/pdf/bouras_2025_ssbse.pdf"
  # - type: code
  #   url: https://github.com/HugoBlox/kit
  # - type: dataset
  #   url: https://github.com/HugoBlox/kit
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: https://github.com/HugoBlox/kit
  # - type: video
  #   url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
