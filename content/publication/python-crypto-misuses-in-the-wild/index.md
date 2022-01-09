---
title: "Python Crypto Misuses in the Wild"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- anna
- Lars Baumgärtner
- Florian Breitfelder
- Mira Mezini

date: "2021-10"
doi: "doi:10.1145/3475716.3484195"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 15th ACM / IEEE International Symposium on Empirical Software Engineering and Measurement (ESEM)*
publication_short: In *ESEM'21*

abstract: Background Previous studies have shown that up to 99.59 % of the Java apps using crypto APIs misuse the API at least once. However, these studies have been conducted on Java and C, while empirical studies for other languages are missing. For example, a controlled user study with crypto tasks in Python has shown that 68.5 % of the professional developers write a secure solution for a crypto task. **Aims** To understand if this observation holds for real-world code, we conducted a study of crypto misuses in Python. **Method** We developed a static analysis tool that covers common misuses of 5 different Python crypto APIs. With this analysis, we analyzed 895 popular Python projects from GitHub and 51 MicroPython projects for embedded devices. Further, we compared our results with the findings of previous studies. **Results** Our analysis reveals that 52.26 % of the Python projects have at least one misuse. Further, some Python crypto libraries' API design helps developers from misusing crypto functions, which were much more common in studies conducted with Java and C code. **Conclusion** We conclude that we can see a positive impact of the good API design on crypto misuses for Python applications. Further, our analysis of MicroPython projects reveals the importance of hybrid analyses.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [cryptographic misuses, Python, API misuse, static analysis, Security]

# Display this page in the Featured widget?
featured: false 

# Custom links (uncomment lines below)
# links:
# - name: Custom LinkWe present the current state of the art of information flow analyses for Go applications. Based on our findings, we discuss future directions of where static analysis information can be used at runtime to for example achieve higher precision, or optimise runtime checks. We focus specifically on outstanding language features such as closures and message-based communication via channels.
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3475716.3484195'
url_code: 'https://github.com/stg-tud/licma'
url_dataset: 'https://github.com/stg-tud/python-crypto-misuses-study-results'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=1sqY5X9j-pw&t=1s'

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
# TODO Get correctly parsed pdf file 
# slides: "python-crypto-misuses-in-the-wild"

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
