---
title: A Decision-Theoretic Perspective on Fairness in Clinical Predictive Models

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Joshua W. Anderson
- Nader Shaikh
- Gregory F. Cooper
- Shyam Visweswaran

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2026-05-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-05-12T15:59:48.320429Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- manuscript

# Publication name and optional abbreviated publication name.
publication: '*Research Square*'
publication_short: ''

doi: 10.21203/rs.3.rs-9644545/v1

abstract: 'Fairness is an important concern in statistical models, especially in clinical prediction models. Most fairness methods focus on model predictions, aiming for parity in model performance across relevant groups. However, this approach overlooks the broader implications of fairness when these models are used in clinical decision-making. We argue that prediction-based fairness frameworks, while valuable, are inherently limited when patient outcomes are equally, if not more, important concerning fairness. We analyze a deployed clinical prediction model, UTICalc, which was revised to improve fairness across racial groups and showed improved performance on a prediction-based fairness metric, namely, equal opportunity (equal true positive rate). We developed a decision-theoretic framework to assess the fairness of UTICalc by integrating patient outcome utilities with model predictions. To this end, we constructed a decision tree to model the clinical decision-making process for assessing and treating urinary tract infection (UTI) in young children, for which UTICalc was developed. Our results show that the revised UTICalc model did not improve an outcome-based fairness metric, namely, expected utility parity. This suggests that prediction-based and outcome-based fairness may diverge, with implications for clinical settings. Furthermore, we suggest that fairness in clinical prediction models should be evaluated based on patient outcomes as well as model predictions.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: 'https://www.researchsquare.com/article/rs-9644545/v1.pdf?c=1778513566000'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
links:
- name: URL
  url: https://doi.org/10.21203/rs.3.rs-9644545/v1
---
