---
title: "Efficient Rendering of Rounded Corners and Edges for Convex Objects"
authors:
- admin
- Sébastien Horna
- Mickaël Ribadière
- Pierre Poulin
- Daniel Meneveaux
date: "2019-06-17T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Computer Graphics Internationnal 2019 Proceeding*
publication_short: In *CGI 2019 Proceeding*

abstract: Any manufactured objects and worn surfaces exhibit rounded corners and edges. These fine details are a source of sharp highlights and shading effects, important to our perception between joining surfaces. However, their representation is often neglected because they introduce complex geometric meshing in very small areas. This paper presents a new method for managing thin rounded corners and edges without explicitly modifying the underlying geometry, so as to produce their visual effects in sample-based rendering algorithms (e.g., ray tracing and path tracing). Our method relies on positioning virtual spheres and cylinders, associated with a detection and acceleration structure that makes the process more robust and more efficient than existing bevel shaders. Moreover, using our implicit surfaces rather than polygonal meshes allows our method to generate extreme close views of the surfaces with a much better visual quality for little additional memory. We illustrate the achieved effects and analyze comparisons generated with existing industrial software shaders.
# Summary. An optional shortened abstract.
summary: any manufactured objects and worn surfaces exhibit rounded corners and edges. These fine details are a source of sharp highlights and shading effects, important to our perception between joining surfaces. However, their representation is often neglected because they introduce complex geometric meshing in very small areas. This paper presents a new method for managing thin rounded corners and edges without explicitly modifying the underlying geometry, so as to produce their visual effects in sample-based rendering algorithms (e.g., ray tracing and path tracing). Our method relies on positioning virtual spheres and cylinders, associated with a detection and acceleration structure that makes the process more robust and more efficient than existing bevel shaders. Moreover, using our implicit surfaces rather than polygonal meshes allows our method to generate extreme close views of the surfaces with a much better visual quality for little additional memory. We illustrate the achieved effects and analyze comparisons generated with existing industrial software shaders.

tags:
- Rendering
- Rounded edges 
- Bevel 
- Chamfer 
- Shading 
- Implicit surface representation
featured: fasle

links:
- name: Supplementals
  url: '#'
url_pdf: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption:
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
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---


