---
title: 'Hot Fixing in the Wild'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Carol Hanna
  - Karine Even-Mendoza 
  - W.B. Langdon
  - Mar Zamorano López 
  - Justyna Petke
  - Federica Sarro

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# date: '2025-07-28'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-06-09'


# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: International Conference on Evaluation and Assessment in Software Engineering (EASE)
# publication_short: Under Review

abstract: 'Despite the operational importance of hot fixes, large-scale evidence on how they reshape routine maintenance workflows, particularly in the era of autonomous coding agents, remains limited. We analyse hot fixes present in over 61 000 GitHub repositories from the Hao-Li/AIDev dataset and find consistent patterns of urgency: reduced collaboration (typically a single contributor), smaller and more targeted changes (median 2–3 commits and files, with ¡10 line modifications), limited review (often fewer than two reviewers), and substantially fewer test file modifications than regular bug fixes, consistent with their urgency-driven character. Leveraging the same urgency contexts, we examine differences between human- and AI-agent-authored hot fixes, revealing over 10 distinct repair behaviours, thus offering insights into future human–automation collaboration for hot fixing. Our study is the first to empirically analyse hot fix code changes at scale using a repository-level operationalisation of urgency. The comparison of human and agent behaviours delineates their distinct characteristics, providing a foundation for understanding hot fixing in real-world practice.' 
tags:
  - Autonomous coding agent
  - Hot fix
  - Automated program repair
  - APR
  - Artificial Intelligence
  - LLM
  - AI bot
  - softbot

# Display this page in the Featured widget?
# featured: true

# Standard identifiers for auto-linking
hugoblox:
  # ids:
  #   doi: 10.5555/123456

# Custom links
links:
  - type: paper
    label: Paper
    url: "https://arxiv.org/abs/2604.26892"
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
