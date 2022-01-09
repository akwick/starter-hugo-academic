---
title: "Don't let data Go astray - A Context-sensitive Taint Analysis for Concurrent Programs in Go"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Ka I Pun 
- Martin Steffen
- Volker Stolz
- anna
- Eric Bodden
- Michael Eichberg 

date: "2016"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2016-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Nordic Workshop on Programming Theory 2016*
publication_short: In *NWPT'16*

abstract: Taint analysis is a form of data flow analysis aiming at secure information flow. For example, unchecked user input is considered typically as *tainted*, i.e., as untrusted and potentially dangerous. Untrusted data may lead to corrupt memory, undermine the correct functioning or privacy concerns of the software otherwise, if it reaches program points it is not supposed to. Many common attack vectors exploit vulnerabilities based on unchecked data and the programmer's negligence of foreseeing all possible user inputs (including malicious ones) and the resulting information flows through the program. We present a static taint analysis for Go, a modern, statically typed programming language. Go in particular features concurrent programming, supporting light-weight threads dubbed *goroutines*, and message-based communication. Beside a classical context-sensitive taint analysis, the paper presents a solution for analyzing channel communication in Go. A longer version of the material will appear in [2].

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [golang, taint analysis, concurrency, static analysis]

# Display this page in the Featured widget?
featured: false 

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://bodden.de/pubs/bep16gotaint.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://www.mn.uio.no/ifi/english/research/projects/goretech/nwpt2016.pdf'
url_source: ''
url_video: ''

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
