---
title: "Joint Rumour Stance and Veracity"
authors:
- lillie
- middelboe
- admin
date: "2019-09-01T00:00:00Z"
doi: ""
publication_types: ["1"]
publication: "Proceedings of the Nordic Conference on Computational Linguistics (NODALIDA)"
abstract: The net is rife with rumours that spread through microblogs and social media. Not all the claims in these can be verified. However, recent work has shown that the stances alone that commenters take toward claims can be sufficiently good indicators of claim veracity, using e.g. an HMM that takes conversational stance sequences as the only input. Existing results are monolingual (English) and mono-platform (Twitter). This paper introduces a stance-annotated Reddit dataset for the Danish language, and describes various implementations of stance classification models. Of these, a Linear SVM provides predicts stance best, with 0.76 accuracy / 0.42 macro F1. Stance labels are then used to predict veracity across platforms and also across languages, training on conversations held in one language and using the model on conversations held in another. In our experiments, monolinugal scores reach stance-based veracity accuracy of 0.83 (F1 0.68); applying the model across languages predicts veracity of claims with an accuracy of 0.82 (F1 0.67). This demonstrates the surprising and powerful viability of transferring stance-based veracity prediction across languages.
summary: 


tags:
#- Source Themes
#featured: true

links:
#- name: Custom Link
#  url: http://example.org
#url_pdf: 'https://www.aclweb.org/anthology/W19-6122.pdf'
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#- internal-project

---
