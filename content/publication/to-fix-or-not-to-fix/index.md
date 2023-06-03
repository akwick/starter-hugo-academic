---
title: "To Fix or Not to Fix: A Critical Study of Crypto-misuses in the Wild"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- anna
- Lars Baumgärtner
- Michael Schlichtig
- Krishna Narasimhan
- Mira Mezini


date: "2022-10"
#doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-09-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2022 IEEE 21th IEEE International Conference on Trust, Security and Privacy in Computing and Communications* 
publication_short: In *TRUSTCOM'22*

abstract: Recent studies have revealed that 87 % to 96 % of the Android apps using cryptographic APIs have a misuse which may cause security vulnerabilities. As previous studies did not conduct a qualitative examination of the validity and severity of the findings, our objective was to understand the findings in more depth. We analyzed a set of 936 open-source Java applications for cryptographic misuses. Our study reveals that 88.10 % of the analyzed applications fail to use cryptographic APIs securely. Through our manual analysis of a random sample, we gained new insights into effective false positives. For example, every fourth misuse of the frequently misused JCA class MessageDigest is an effective false positive due to its occurrence in a non-security context. As we wanted to gain deeper insights into the security implications of these misuses, we created an extensive vulnerability model for cryptographic API misuses. Our model includes previously undiscussed attacks in the context of cryptographic APIs such as DoS attacks. This model reveals that nearly half of the misuses are of high severity, e.g., hard-coded credentials and potential Man-in-the-Middle attacks.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [cryptography, API misuse, static analysis, false positives]

# Display this page in the Featured widget?
featured: false 

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: 'https://doi.org/10.6084/m9.figshare.21178243'
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
