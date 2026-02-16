---
title: 'Applying Genetic Improvement Techniques for Automated Program Repair of Transpiled Code'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Prasham Jadhwani
  - Carol Hanna
  - William B. Langdon
  - Justyna Petke

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# date: '2023-12-10'

# Schedule page publish date (NOT publication's date).
date: '2026-01-01'


# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In International Workshop on Genetic Improvement@ ICSE
# publication_short: In International symposium on search based software engineering

abstract: We use Genetic Improvement (GI)-based Automated Program Repair (APR) techniques for syntax correction on transpiled code produced by both large language models (LLMs) and rule-based translators. A three-stage pipeline was developed, combining rule- based test generation, an optional LLM-driven preprocessing stage for syntax correction, and GI-based repair strategies. LLM-assisted Type Change Operator and Boolean Value Change Operator were added to the MAGPIE GI framework, which reduced transpilation bugs from Python to Java by 33% (LLM) and by 18% on rule-based translations. A comprehensive taxonomy of common transpilation bugs was developed, mapping faults to mutation operators, alongside an evaluation of the effectiveness of secondary LLM interventions.

tags:
  - Code Transpilation
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
    url: "https://solar.cs.ucl.ac.uk/pdf/jadhwani_2026_GI.pdf"
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
