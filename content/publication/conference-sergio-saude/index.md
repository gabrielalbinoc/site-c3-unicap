---
title: 'Performance Improvement of Path Planning algorithms with Deep Learning Encoder Model'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Bruno José Torres Fernandes
  - Janderson Ferreira
  - Agostinho A. F. Junior
  - Yves M. Galvão
  - Pablo Barros
  - sergio

# Author notes (optional)
author_notes:
#  - 'Equal contribution'
# - 'Equal contribution'

date: '2020-09-26T00:00:00Z'
doi: '10.1109/ICDL-EpiRob48136.2020.9278050'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-19T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE*

abstract: Currently, path planning algorithms are used in many daily tasks. They are relevant to find the best route in traffic and make autonomous robots able to navigate. The use of path planning presents some issues in large and dynamic environments. Large environments make these algorithms spend much time finding the shortest path. On the other hand, dynamic environments request a new execution of the algorithm each time a change occurs in the environment, and it increases the execution time. The dimensionality reduction appears as a solution to this problem, which in this context means removing useless paths present in those environments. Most of the algorithms that reduce dimensionality are limited to the linear correlation of the input data. Recently, a Convolutional Neural Network (CNN) Encoder was used to overcome this situation since it can use both linear and non-linear information to reduce data. This paper analyzes in-depth the performance to eliminate the useless paths using this CNN Encoder model. To measure the mentioned model efficiency, we combined it with different path planning algorithms. Next, the final algorithms (combined and not combined) are checked in a database composed of five scenarios. Each scenario contains fixed and dynamic obstacles. Their proposed model, the CNN Encoder, associated with other existent path planning algorithms in the literature, was able to obtain a time decrease to find the shortest path compared to all path planning algorithms analyzed. the average decreased time was 54.43%.

# Summary. An optional shortened abstract.
#summary
tags: [Machine Learning,Articificial Intelligence,computer vision and patter recognotion]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
  - name: IEE
    url: https://ieeexplore.ieee.org/abstract/document/9278050/


# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}
