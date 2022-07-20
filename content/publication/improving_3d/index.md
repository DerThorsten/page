---
title: 'Improving 3D EM data segmentation by joint optimization over boundary evidence and biological priors'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Nikola Krasowski
  - admin
  - Graham W Knott
  - Ullrich Koethe
  - Fred A Hamprecht
  - Anna Kreshuk

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2015-04-16T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2015-04-16T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In 2011 International Conference on Computer Vision
publication_short: In ICCV

abstract: "
Beschreibung
We present a new automated neuron segmentation algorithm for isotropic 3D electron microscopy data. We cast the problem into the asymmetric multiway cut framework. The latter combines boundary-based segmentation (clustering) with region-based segmentation (semantic labeling) in a single problem and objective function. This joint formulation allows us to augment local boundary evidence with higherlevel biological priors, such as membership to an axonic or dendritic neurite. Joint optimization enforces consistency between evidence and priors, leading to correct resolution of many difficult boundary configurations. We show experimentally on a FIB/SEM dataset of mouse cortex that the new approach outperforms existing hierarchical segmentation and multicut algorithms which only use boundary evidence."

# Summary. An optional shortened abstract.
summary: "
Beschreibung
We present a new automated neuron segmentation algorithm for isotropic 3D electron microscopy data. We cast the problem into the asymmetric multiway cut framework. The latter combines boundary-based segmentation (clustering) with region-based segmentation (semantic labeling) in a single problem and objective function. This joint formulation allows us to augment local boundary evidence with higherlevel biological priors, such as membership to an axonic or dendritic neurite. Joint optimization enforces consistency between evidence and priors, leading to correct resolution of many difficult boundary configurations. We show experimentally on a FIB/SEM dataset of mouse cortex that the new approach outperforms existing hierarchical segmentation and multicut algorithms which only use boundary evidence."

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://hci.iwr.uni-heidelberg.de/sites/default/files/publications/files/768610281/krasowski_15_improving.pdf'
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