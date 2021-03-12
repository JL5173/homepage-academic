---
title: "Event-driven Consumption Intent Reasoning Using Heterogeneous Graph Neural Networks with Meta-Topology"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Bibo Cai
- Xiao Ding

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2021-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The 44th International ACM SIGIR Conference on Research and Development in Information Retrieval*
publication_short: In *SIGIR 2021*

abstract: Event-driven Consumption Intent refers to one’s consumption intent to certain types of products triggered by a daily event. However, little prior work attempts to explicitly model the relationship between events and consumption intentions. To fill this gap, we propose to automatically construct a novel knowledge base — Event-Consumption Graph (ECG) as a complement to the existing KBs. Specifically, ECG is a heterogeneous graph that contains two types of nodes: event nodes and product nodes, and three types of edges: event-event edges, event-product edges and product-product edges. Due to the semantic complexity and expressive diversity of events, ECG can suffer from the sparsity problem. To improve the coverage of ECG, we propose a new task Event-driven Consumption Intent Reasoning (ECIR) to complement the ECG. The main challenge of this task is that conventional heterogeneous graph neural network reasoning relies on localized first-order structure information in the single-view network that is unable to capture higher-order heterogeneous interactions between nodes. To address this issue, we present a Meta-Topology based Heterogeneous Graph Neural Network (MT-HGNN), which utilizes meta-topology induced subgraph adjacency matrix to capture node’s local high-order heterogeneous connection features. A novel multi-view information aggregation mechanism is applied to allow each node to select the best reasoning.

# Summary. An optional shortened abstract.
summary: We present a Meta-Topology based Heterogeneous Graph Neural Network (MT-HGNN), which utilizes meta-topology induced subgraph adjacency matrix to capture node’s local high-order heterogeneous connection features to deal with ECIR task.

tags: []

# Display this page in the 

 widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://paper1.org

url_pdf: ''
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
