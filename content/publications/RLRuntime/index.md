---
title: 'Enhancing software runtime with reinforcement learning-driven mutation operator selection in genetic improvement'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Damien Bose
  - Carol Hanna
  - Justyna Petke

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# date: '2023-12-10'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-04-27'


# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In IEEE/ACM International Workshop on Genetic Improvement (GI)
# publication_short: In International symposium on search based software engineering

abstract: Genetic Improvement employs heuristic search algorithms to explore the search space of program variants by modifying code using mutation operators. This research focuses on operators that delete, insert and replace source code statements. Traditionally, in GI an operator is chosen uniformly at random at each search iteration. This work leverages Reinforcement Learning to intelligently guide the selection of these operators specifically to improve program runtime. We propose to integrate RL into the operator selection process. Four Multi-Armed bandit RL algorithms (Epsilon Greedy, UCB, Probability Matching, and Policy Gradient) were integrated within a GI framework, and their efficacy and efficiency were benchmarked against the traditional GI operator selection approach. These RL-guided operator selection strategies have demonstrated empirical superiority over the traditional GI methods of randomly selecting a search operator, with UCB emerging as the top-performing RL algorithm. On average, the UCBguided Hill Climbing search algorithm produced variants that compiled and passed all tests 44 % of the time, while only 22 % of the variants produced by the traditional uniform random selection strategies compiled and passed all tests.

tags:
  - Runtime
  - Genetic Improvement
  - Reinforcement Learning

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
    url: "https://ieeexplore.ieee.org/abstract/document/11029541"
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
