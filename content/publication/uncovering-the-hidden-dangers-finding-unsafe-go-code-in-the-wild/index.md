---
title: "Uncovering the Hidden Dangers: Finding Unsafe Go Code in the Wild"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Johannes Lauinger
- Lars Baumgärtner
- anna
- Mira Mezini
author_notes:
- 
- "Equal contribution"
- "Equal contribution"
- 

date: "2020-12"
doi: "doi:10.1007/978-3-319-47166-2_30"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2020 IEEE 19th IEEE International Conference on Trust, Security and Privacy in Computing and Communications*
publication_short: In *TRUSTCOM'20*

abstract: We present the current state of the art of information flow analyses for Go applications. Based on our findings, we discuss future directions of where static analysis information can be used at runtime to for example achieve higher precision, or optimise runtime checks. We focus specifically on outstanding language features such as closures and message-based communication via channels.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [golang, API misuse, static analysis, security, unsafe API]

# Display this page in the Featured widget?
featured: false 

# Custom links (uncomment lines below)
# links:
# - name: Custom LinkWe present the current state of the art of information flow analyses for Go applications. Based on our findings, we discuss future directions of where static analysis information can be used at runtime to for example achieve higher precision, or optimise runtime checks. We focus specifically on outstanding language features such as closures and message-based communication via channels.
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2010.11242'
url_code: 'https://github.com/stg-tud/go-geiger'
url_code: 'https://github.com/stg-tud/go-safer'
url_dataset: 'https://zenodo.org/record/4130780'
url_poster: ''
url_project: ''
url_slides: ''
# url_source: 'https://github.com/stg-tud/unsafe_go_study_results'
url_video: 'https://www.youtube.com/watch?v=adn6A7nG61I'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example

# {{% callout note %}}
# Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}
# 
# {{% callout note %}}
# Create your slides in Markdown - click the *Slides* button to check out the example.
# {{% /callout %}}
# 
# Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
---
