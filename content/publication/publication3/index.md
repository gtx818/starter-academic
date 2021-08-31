---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "RGB-D Visual SLAM for Mobile Robots"
authors: 
- admin
- Shao Chen
- Yuxiang Guo
- Tianxiao Gao
- Qingyuan Gong
- Junguo Zhang

date: "2018-07-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Transactions of the Chinese Society for Agricultural Machinery*
# publication_short: In *ISPECE*

abstract: "In view of the problems of low accuracy and poor real-time in the research of visual simultaneous localization and mapping, a RGB-D vision SLAM algorithm for indoor mobile robots was proposed．Firstly, feature points of RGB image were extracted by using oriented fast and rotated brief (ORB) algorithm, and matching point pair set was obtained by the bidirectional K-nearest neighbor (KNN) feature matching method based on fast library for approximate nearest neighbors (FLANN). The improved random sampling consistency algorithm (RE-RANSAC) was used to eliminate false matching points and estimate the 6D motion transformation model between two adjacent images, as the initial transformation model of GICP algorithm．The generalized iterative closest point algorithm (GICP) was used to obtain the optimized motion transformation model, and then the pose diagram was obtained．In order to improve the positioning accuracy, a random closed-loop detection link was introduced to reduce the cumulative error in the robot positioning process, and the pose diagram was optimized by using the general graph optimization (G2O) method to obtain the global optimal pose diagram and camera motion trajectory, and the global color dense point cloud map was finally generated．For the tested FR1 data sets, the minimum positioning error of the algorithm was 0. 011 m, the average positioning error was 0. 024 5 m, and the average processing time of each frame was 0. 032 s, which can meet the requirement of rapid positioning and mapping of mobile robots."

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