---
title: "Uncertainty quantification in time-lapse seismic imaging: a full-waveform approach"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Maria Kotsi
- Alison Malcolm
- Gregory Ely

date: ""
doi: "10.1093/gji/ggaa245"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Geophysical Journal International*
publication_short: In *GJI*

abstract: Time-lapse seismic monitoring using full-wavefield methods aims to accurately and robustly image rock and fluid changes within a reservoir. These changes are typically small and localized. Quantifying the uncertainty related to these changes is crucial for decision making, but traditional methods that use pixel by pixel uncertainty quantification with large models are computationally infeasible. We exploit the structure of the time-lapse seismic problem for fast wavefield computations using a numerically exact local acoustic solver. This allows us to perform a Bayesian inversion using a Metropolis–Hastings algorithm to sample our posterior distribution. We address the well-known dimensionality problem in global optimization using an image compression technique. We run our numerical experiments using a single shot and a single frequency, however we show that various frequencies converge to different local minima. In addition, we test our framework for both uncorrelated and correlated noise, and we retrieve different histograms for each noise type. Through our numerical examples we show the importance of defining quantities of interest in order to setup an appropriate uncertainty quantification framework involving choosing the number of degrees of freedom and model parametrization that best approximate the problem. To our knowledge, there is no work in the literature studying the time-lapse problem using stochastic full-waveform inversion.

tags: ["Inverse Theory", "Probability distributions", "Waveform Inversion", "Computational Seismology", "Controlled source seismology", "Statistical seismology"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://academic.oup.com/gji/article-abstract/222/2/1245/5838038'
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
projects:[]


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
