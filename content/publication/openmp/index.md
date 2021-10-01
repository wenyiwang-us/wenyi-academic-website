---
title: "Paths to OpenMP in the Kernel"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jiacheng Ma
- admin
- Aaron Nelson
- Michael Cuevas
- Brian Homerding
- Conghao Liu
- Zhen Huang
- Simone Campanoni
- Kyle Hale
- Peter Dinda

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2021-08-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *SC21*
publication_short: In *SC21*

abstract: OpenMP implementations make increasing demands on the kernel. We take the next step and consider bringing OpenMP into the kernel. Our vision is that the entire OpenMP application, run-time system, and a kernel framework is interwoven to become the kernel, allowing the OpenMP implementation to take full advantage of the hardware in a custom manner. We compare and contrast three approaches to achieving this goal. The first, runtime in kernel (RTK), ports the OpenMP runtime to the kernel, allowing any kernel code to use OpenMP pragmas. The second, process in kernel (PIK) adds a specialized process abstraction for running user-level OpenMP code within the kernel. The third, custom compilation for kernel(CCK), compiles OpenMP into a form that leverages the kernel framework without any intermediaries. We describe the design and implementation of these approaches, and evaluate them using NAS and other benchmarks.

# Summary. An optional shortened abstract.
summary: We bring OpenMP into the kernel so that the entire OpenMP application, runtime system and a kernel framework is interwoven to become the kernel, allowing the OpenMP implementation to take full advantage of the hardware in a custom manner.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/openmp/MODERN_SC_2021.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example

design:
  view: 4
---


