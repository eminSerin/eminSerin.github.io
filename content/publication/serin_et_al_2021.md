---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "NBS-Predict: A prediction-based extension of the network-based statistic"
authors: ["Emin Serin","Andrew Zalesky","Adu Matory","Henrik Walter","Johann Kruschwitz"]
date: 2021-10-06T13:26:24+03:00
doi: "10.1016/j.neuroimage.2021.118625"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-10-06T13:26:24+03:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "NBS-Predict: A prediction-based extension of the network-based statistic"
publication_short: ""

abstract: "Graph models of the brain hold great promise as a framework to study functional and structural brain connectivity across scales and species. The network-based statistic (NBS) is a well-known tool for performing statistical inference on brain graphs, which controls the family-wise error rate in a mass univariate analysis by combining the cluster-based permutation technique and the graph-theoretical concept of connected components. As the NBS is based on group-level inference statistics, it does not inherently enable informed decisions at the level of individuals, which is, however, necessary for the realm of precision medicine. Here we introduce NBS-Predict, a new approach that combines the powerful features of machine learning (ML) and the NBS in a user-friendly graphical user interface (GUI). By combining ML models with connected components in a cross-validation (CV) structure, the new methodology provides a fast and convenient tool to identify generalizable neuroimaging-based biomarkers. The purpose of this paper is to (i) introduce NBS-Predict and evaluate its performance using two sets of simulated data with known ground truths, (ii) demonstrate the application of NBS-Predict in a real case-control study, including resting-state functional magnetic resonance imaging (rs-fMRI) data acquired from patients with schizophrenia, (iii) evaluate NBS-Predict using rs-fMRI data from the Human Connectome Project 1200 subjects release. We found that: (i) NBS-Predict achieved good statistical power on two sets of simulated data; (ii) NBS-Predict classified schizophrenia with an accuracy of 90% using subjects’ functional connectivity matrices and identified a subnetwork with reduced connections in the group with schizophrenia, mainly comprising brain regions localized in frontotemporal, visual, and motor areas, as well as in the subcortex; (iii) NBS-Predict also predicted general intelligence scores from resting-state fMRI connectivity matrices with a prediction score of r = 0.2 and identified a large-scale subnetwork associated with general intelligence. Overall results showed that NBS-Predict performed comparable to or better than pre-existing feature selection algorithms (lasso, elastic net, top 5%, p-value thresholding) and connectome-based predictive modeling (CPM) in terms of identifying relevant features and prediction accuracy."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://www.sciencedirect.com/science/article/pii/S1053811921008983"
url_code: "https://github.com/eminSerin/NBS-Predict"
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
