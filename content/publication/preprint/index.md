---
title: "Morphological Simulation Tests the Limits on Phenotype Discovery in 3D Image Analysis"
authors:
- Rachel A. Roston
- admin
- Sara M. Rolfe
- Murat A. Maga
date: "2024-07-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-31T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: In the past few decades, advances in 3D imaging have created new opportunities for reverse genetic screens. Rapidly growing datasets of 3D images of genetic knockouts require high-throughput, automated computational approaches for identifying and characterizing new phenotypes. However, exploratory, discovery-oriented image analysis pipelines used to discover these phenotypes can be difficult to validate because, by their nature, the expected outcome is not known a priori. Introducing known morphological variation through simulation can help distinguish between real phenotypic differences and random variation; elucidate the effects of sample size; and test the sensitivity and reproducibility of morphometric analyses. Here we present a novel approach for 3D morphological simulation that uses open-source, open-access tools available in 3D Slicer, SlicerMorph, and Advanced Normalization Tools in R (ANTsR). While we focus on diffusible-iodine contrast-enhanced micro-CT (diceCT) images, this approach can be used on any volumetric image. We then use our simulated datasets to test whether tensor-based morphometry (TBM) can recover our introduced differences; to test how effect size and sample size affect detectability; and to determine the reproducibility of our results. In our approach to morphological simulation, we first generate a simulated deformation based on a reference image and then propagate this deformation to subjects using inverse transforms obtained from the registration of subjects to the reference. This produces a new dataset with a shifted population mean while retaining individual variability because each sample deforms more or less based on how different or similar it is from the reference. TBM is a widely-used technique that statistically compares local volume differences associated with local deformations. Our results showed that TBM recovered our introduced morphological differences, but that detectability was dependent on the effect size, the sample size, and the region of interest (ROI) included in the analysis. Detectability of subtle phenotypes can be improved both by increasing the sample size and by limiting analyses to specific body regions. However, it is not always feasible to increase sample sizes in screens of essential genes. Therefore, methodical use of ROIs is a promising way to increase the power of TBM to detect subtle phenotypes. Generating known morphological variation through simulation has broad applicability in developmental, evolutionary, and biomedical morphometrics and is a useful way to distinguish between a failure to detect morphological difference and a true lack of morphological difference. Morphological simulation can also be applied to AI-based supervised learning to augment datasets and overcome dataset limitations.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Morphometrics


featured: true

links:
- name: Original Article
  url: https://www.biorxiv.org/content/early/2024/07/02/2024.06.30.601430
url_pdf: https://www.biorxiv.org/content/10.1101/2024.06.30.601430v1.full.pdf
url_code: 'https://github.com/raroston/SimMorph'
#url_dataset: 'https://github.com/raroston/SimMorph'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'






# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
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

This work is driven by the results in [MEMOS](/publication/journal-article/).


