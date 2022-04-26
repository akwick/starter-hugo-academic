---
title: "CamBench - Cryptographic API Misuse Detection Tool Benchmark Suite"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Michael Schlichtig
- anna
- Stefan Krüger
- Eric Bodden
- Mira Mezini

author_notes:
- "Equal contribution"
- "Equal contribution"
- 
-
-

date: "2022"
doi: "https://doi.org/10.48550/arXiv.2204.06447"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-04-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: accepted at *MSR 2022 Registered Reports Track* as In-Principal Acceptance (IPA)
publication_short: In *MSR*

Context Cryptographic APIs are often misused in real-world applications. Therefore, many cryptographic API misuse detection tools have been introduced. However, there exists no established reference benchmark for a fair and comprehensive comparison and evaluation of these tools. While there are benchmarks, they often only address a subset of the domain or were only used to evaluate a subset of existing misuse detection tools. Objective To fairly compare cryptographic API misuse detection tools and to drive future development in this domain, we will devise such a benchmark. Openness and transparency in the generation process are key factors to fairly generate and establish the needed benchmark. Method We propose an approach where we derive the benchmark generation methodology from the literature which consists of general best practices in benchmarking and domain-specific benchmark generation. A part of this methodology is transparency and openness of the generation process, which is achieved by pre-registering this work. Based on our methodology we design CamBench, a fair "Cryptographic API Misuse Detection Tool Benchmark Suite". We will implement the first version of CamBench limiting the domain to Java, the JCA, and static analyses. Finally, we will use CamBench to compare current misuse detection tools and compare CamBench to related benchmarks of its domain.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [cryptography, benchmark, API misuse, static analysis]

# Display this page in the Featured widget?
featured: false 

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2204.06447.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'The overview slide from the presentation presenting an insecure code example, the approach to create the data set, the evaluation results, and future research ideas as well as the URL to the data set.'
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
