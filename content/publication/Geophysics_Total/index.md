---
title: "Combining reflection and transmission information in time-lapse velocity inversion: A new hybrid approach"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Maria Kotsi
- Jonathan Edgar
- Alison Malcolm
- Sjoerd de Ridder

date: "2019-06-18"
doi: "10.1190/geo2018-0086.1"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Geophysics*
publication_short: In *Geophysics*

abstract: Full-waveform inversion (FWI) uses the information of the full wavefield to deliver high-resolution images of the subsurface. Conventional time-lapse FWI primarily uses the transmitted component (diving waves) of the wavefield to reconstruct the low-wavenumber component of the velocity model. This requires large-offset surveys and low-frequency data. When the target of interest is deep, diving waves cannot reach the target and FWI will be dominated by the reflected component of the wavefield. Consequently, the retrieved model resembles a least-squares migration instead of a velocity model. Image-domain methods, especially image-domain wavefield tomography (IDWT), have been developed to obtain a model of time-lapse velocity changes in deeper targets using reflected waves. The method is able to recover models of deep targets. However, it also tends to obtain smeared time-lapse velocity changes. We have developed a form of time-lapse waveform inversion that we call dual-domain time-lapse waveform inversion (DDWI), whose objective function joins FWI and IDWT, combining information from the diving waves in the data-domain FWI term with information from the reflected waves in the image-domain IDWT term. During the nonlinear inversion, the velocity model is updated using constraints from both terms simultaneously. Similar to sequential time-lapse waveform inversion, we start the time-lapse inversion from a baseline model recovered with FWI. We test DDWI on a variety of synthetic models of increasing complexity and find that it can recover time-lapse velocity changes more accurately than when both methods are used independently or sequentially.

tags: ["Full Waveform Inversion", "Time Lapse Seismic Imaging", "Image Domain Waveform Inversion",  "Controlled source seismology"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://library.seg.org/doi/10.1190/geo2018-0086.1'
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
  caption: ''
  focal_point: "Center"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
