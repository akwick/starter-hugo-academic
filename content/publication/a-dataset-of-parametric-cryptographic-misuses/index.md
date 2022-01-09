---
title: "A Dataset of Parametric Cryptographic Misuses"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- anna
- Michael Reif
- Michael Eichberg 
- Anam Dodhy
- Mira Mezini

date: "2019-05"
doi: "10.1109/MSR.2019.00023"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-05-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 16th International Conference on Mining Software Repositories"
publication_short: In *MSR'19*

abstract: Cryptographic APIs (Crypto APIs) provide the foundations for the development of secure applications. Unfortunately, most applications do not use Crypto APIs securely and end up being insecure, e.g., by the usage of an outdated algorithm, a constant initialization vector, or an inappropriate hashing algorithm. Two different studies [1], [2] have recently shown that 88% to 95% of those applications using Crypto APIs are insecure due to misuses. To facilitate further research on these kinds of misuses, we created a collection of 201 misuses found in real-world applications along with a classification of those misuses. In the provided dataset, each misuse consists of the corresponding open-source project, the project's build information, a description of the misuse, and the misuse's location. Further, we integrated our dataset into MUBench [3], a benchmark for API misuse detection. Our dataset provides a foundation for research on Crypto API misuses. For example, it can be used to evaluate the precision and recall of detection tools, as a foundation for studies related to Crypto API misuses, or as a training set.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [cryptographic misuse, API-misuse, dataset, benchmark]

# Display this page in the Featured widget?
featured: false 

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'a-dataset-of-parametric-cryptographic-misuses/a-dataset-of-parametric-cryptographic-misuses.pdf'
url_code: 'https://zenodo.org/record/2558580'
url_dataset: 'https://github.com/stg-tud/MUBench/pull/427'
url_poster: ''
url_project: ''
url_slides: '2019_05_27_MSR_A-dataset-of-parametric-cryptographic-misuses.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
 caption: 'The overview slide from the presentation presenting an insecure code example, the approach to create the data set, the evaluation results, and future research ideas as well as the URL to the data set.'
 focal_point: ""
 preview_only: false

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
