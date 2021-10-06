+++
title = "NBS-Predict: A prediction-based extension of the network-based statistic"
date = 2021-12-01
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Emin Serin","Andrew Zalesky","Adu Matory","Henrik Walter","Johann Kruschwitz"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*NeuroImage*"

# Abstract and optional shortened version.
abstract = "Graph models of the brain hold great promise as a framework to study functional and structural brain connectivity across scales and species. The network-based statistic (NBS) is a well-known tool for performing statistical inference on brain graphs, which controls the family-wise error rate in a mass univariate analysis by combining the cluster-based permutation technique and the graph-theoretical concept of connected components. As the NBS is based on group-level inference statistics, it does not inherently enable informed decisions at the level of individuals, which is, however, necessary for the realm of precision medicine. Here we introduce NBS-Predict, a new approach that combines the powerful features of machine learning (ML) and the NBS in a user-friendly graphical user interface (GUI). By combining ML models with connected components in a cross-validation (CV) structure, the new methodology provides a fast and convenient tool to identify generalizable neuroimaging-based biomarkers. The purpose of this paper is to (i) introduce NBS-Predict and evaluate its performance using two sets of simulated data with known ground truths, (ii) demonstrate the application of NBS-Predict in a real case-control study, including resting-state functional magnetic resonance imaging (rs-fMRI) data acquired from patients with schizophrenia, (iii) evaluate NBS-Predict using rs-fMRI data from the Human Connectome Project 1200 subjects release. We found that: (i) NBS-Predict achieved good statistical power on two sets of simulated data; (ii) NBS-Predict classified schizophrenia with an accuracy of 90% using subjects’ functional connectivity matrices and identified a subnetwork with reduced connections in the group with schizophrenia, mainly comprising brain regions localized in frontotemporal, visual, and motor areas, as well as in the subcortex; (iii) NBS-Predict also predicted general intelligence scores from resting-state fMRI connectivity matrices with a prediction score of r = 0.2 and identified a large-scale subnetwork associated with general intelligence. Overall results showed that NBS-Predict performed comparable to or better than pre-existing feature selection algorithms (lasso, elastic net, top 5%, p-value thresholding) and connectome-based predictive modeling (CPM) in terms of identifying relevant features and prediction accuracy."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://www.sciencedirect.com/science/article/pii/S1053811921008983"
url_preprint = ""
url_code = "https://github.com/eminSerin/NBS-Predict"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true
+++