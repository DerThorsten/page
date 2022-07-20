---
title: 'Solving large multicut problems for connectomics via domain decomposition'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Constantin Pape
  - admin
  - Peter Li
  - Viren Jain
  - Davi D. Bock
  - Anna Kreshuk

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2017-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Proceedings of the IEEE International Conference on Computer Vision Workshops 2017
publication_short: In ICCV 2017

abstract: "For image segmentation, recent advances in optimization
make it possible to combine noisy region appearance terms with pairwise terms which can not only discourage, but also encourage label transitions, depending on boundary evidence. These models have the potential to overcome problems such as the shrinking bias. However, with the
ability to encourage label transitions comes a different problem: strong
boundary evidence can overrule weak region appearance terms to create new regions out of nowhere. While some label classes exhibit strong
internal boundaries, such as the background class which is the pool of
objects. Other label classes, meanwhile, should be modeled as a single
region, even if some internal boundaries are visible.
We therefore propose in this work to treat label classes asymmetrically:
for some classes, we allow a further partitioning into their constituent
objects as supported by boundary evidence; for other classes, further
partitioning is forbidden. In our experiments, we show where such a
model can be useful for both 2D and 3D segmentation."

# Summary. An optional shortened abstract.
summary: "For image segmentation, recent advances in optimization
make it possible to combine noisy region appearance terms with pairwise terms which can not only discourage, but also encourage label transitions, depending on boundary evidence. These models have the potential to overcome problems such as the shrinking bias. However, with the
ability to encourage label transitions comes a different problem: strong
boundary evidence can overrule weak region appearance terms to create new regions out of nowhere. While some label classes exhibit strong
internal boundaries, such as the background class which is the pool of
objects. Other label classes, meanwhile, should be modeled as a single
region, even if some internal boundaries are visible.
We therefore propose in this work to treat label classes asymmetrically:
for some classes, we allow a further partitioning into their constituent
objects as supported by boundary evidence; for other classes, further
partitioning is forbidden. In our experiments, we show where such a
model can be useful for both 2D and 3D segmentation."

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'http://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w1/Pape_Solving_Large_Multicut_ICCV_2017_paper.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
#slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
 -->