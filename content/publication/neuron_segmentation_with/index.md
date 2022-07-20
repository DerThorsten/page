---
title: 'Neuron segmentation with high-level biological priors'

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

date: '2017-06-06T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-06-06T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Medical Imaging
publication_short: IEEE Transactions on Medical Imaging

abstract: "We present a novel approach to the problem of neuron segmentation in image volumes acquired by an electron microscopy. Existing methods, such as agglomerative or correlation clustering, rely solely on boundary evidence and have problems where such an evidence is lacking (e.g., incomplete staining) or ambiguous (e.g., co-located cell and mitochondria membranes). We investigate if these difficulties can be overcome by means of sparse region appearance cues that differentiate between pre- and postsynaptic neuron segments in mammalian neural tissue. We combine these cues with the traditional boundary evidence in the asymmetric multiway cut (AMWC) model, which simultaneously solves the partitioning and the semantic region labeling problems. We show that AMWC problems over superpixel graphs can be solved to global optimality with a cutting plane approach, and that the introduction of semantic class priors leads to significantly better segmentations."

# Summary. An optional shortened abstract.
summary: "We present a novel approach to the problem of neuron segmentation in image volumes acquired by an electron microscopy. Existing methods, such as agglomerative or correlation clustering, rely solely on boundary evidence and have problems where such an evidence is lacking (e.g., incomplete staining) or ambiguous (e.g., co-located cell and mitochondria membranes). We investigate if these difficulties can be overcome by means of sparse region appearance cues that differentiate between pre- and postsynaptic neuron segments in mammalian neural tissue. We combine these cues with the traditional boundary evidence in the asymmetric multiway cut (AMWC) model, which simultaneously solves the partitioning and the semantic region labeling problems. We show that AMWC problems over superpixel graphs can be solved to global optimality with a cutting plane approach, and that the introduction of semantic class priors leads to significantly better segmentations."

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/7940079'
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