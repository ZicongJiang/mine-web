+++
title = "A lightweight fast object detection method [Accepted]"
date = 2021-09-13T00:00:00

# Authors. Comma separated list, e.g. `["BAob Smith", "David Jones"]`.
authors = ["Yanfei Jia","Guangda Chen","Zicong Jiang","Miao Yang","Liyun Xing"]
# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Preprint / Working Paper
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = Thesis
# 8 = Patent
publication_types = ["2"]

# Publication name and optional abbreviated version.
# publication = "In *Source Themes Conference*"
# publication_short = "In *STC*"

# Abstract.
abstract: "The “You only look once (version 4)-tiny ” method is proposed based on “You only look once (version 4)” to simple the network structure and reduce parameters, which makes it be suitable for developing on the mobile and embedded devices. To speed up the object detection on devices that have limited computing power, a fast object detection method is proposed on the basis of “You only look once (version 4)-tiny”. It firstly uses two ResBlock-D modules in ResNet-D network instead of two CSPBlock modules in “You only look once (version 4)-tiny”, which reduces the computation complexity. Secondly, it designs an auxiliary residual network block to extract more feature information of object to reduce detection error. In the design of auxiliary network, two consecutive 3x3 convolutions are used to obtain 5x5 receptive fields to extract global features, and channel attention and spatial attention are also used to extract more effective information. In the end, it merges the auxiliary network and backbone network to construct the whole network structure of proposed method. Simulation results show that the proposed method has faster object detection than “You only look once (version 4)-tiny” and “You only look once (version 3)-tiny”, and almost the same mean value of average precision as the “You only look once (version 4)-tiny”. It is more suitable for real-time object detection.

# Summary. An optional shortened abstract.
summary = "Journal of Network Intelligence. JNI-0210, 2021-09-13"

# Digital Object Identifier (DOI)
#doi = ""

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
#tags = ["Source Themes"]

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects = ["internal-project"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides = "example"

# Links (optional).
#url_pdf = "https://arxiv.org/ftp/arxiv/papers/2011/2011.04244.pdf"
#url_code = "#"
#url_dataset = "#"
#url_project = ""
#url_slides = ""
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#links = [{name = "Custom Link", url = "http://example.org"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
