---
title: "Handle the problem of ample label space by using the Image-guided Feature Extractor on the MUSTI dataset"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Duc-Le Ngoc
  - Hung-Le Minh
  - Dinh-Vinh Quang
# Author notes (optional)
author_notes:
  - "Equal contribution"
  - "Equal contribution"

date: "2024-02-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-05-29T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *Multimedia Evaluation Workshop*
publication_short: In *MMM*

abstract: Among multimodal tasks, olfactory perception remains a largely unexplored field. The two most significant difficulties that need to be overcome are that the label space is ample while the data set size is generally of too small volume. The second is the imbalanced nature of labels in the data set. In this paper, we develop and evaluate our model in the task of predicting the congruence of olfactory experiences between an image and a corresponding text passage on the MUSTI dataset. To solve the label imbalance problem and optimize the process of extracting multimedia images and text with large feature spaces, we propose a model that selectively selects the text features based on image features. By selecting texts that need attention, our model outperforms existing baselines on training and testing data sets.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Vison Language

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: "https://ceur-ws.org/Vol-3658/paper5.pdf"
url_code: "git@github.com:HungLM1506/MMM2024.git"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: "[**Architecture**](Architecture.png)"
  focal_point: ""
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
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
