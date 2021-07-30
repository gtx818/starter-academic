---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "CI-Net: Contextual Information for Joint Semantic Segmentation and Depth Estimation"
authors: 
- admin
- Wu Wei
- Zhongbin Cai
- Zhun Fan
- Shane Xie
- Xinmei Wang
- Qiuda Yu

date: "2021-07-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *arxiv.2107.13800*
# publication_short: In *ISPECE*

abstract: "Monocular depth estimation and semantic segmentation are two fundamental goals of scene understanding. Due to the advantages of task interaction, many works study the joint task learning algorithm. However, most existing methods fail to fully leverage the semantic labels, ignoring the provided context structures and only using them to supervise the prediction of segmentation split. In this paper, we propose a network injected with contextual information (CI-Net) to solve the problem. Specifically, we introduce self-attention block in the encoder to generate attention map. With supervision from the ground truth created by semantic labels, the network is embedded with contextual information so that it could understand the scene better, utilizing dependent features to make accurate prediction. Besides, a feature sharing module is constructed to make the task-specific features deeply fused and a consistency loss is devised to make the features mutually guided. We evaluate the proposed CI-Net on the NYU-Depth-v2 and SUN-RGBD datasets. The experimental results validate that our proposed CI-Net is competitive with the state-of-the-arts."

# Summary. An optional shortened abstract.
# summary: ""

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: 'https://arxiv.org/abs/2107.13800v1'
# url_code:
# url_dataset:
# url_poster:
# url_project:
# url_slides:
# url_source:
# url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "featured.png"
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
<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Click the *Images* button 
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->
<!-- 
Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->