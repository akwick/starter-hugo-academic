---
title: "A Fine-grained Data Set and Analysis of Tangling in Bug Fixing Commits"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Steffen Herbold
- Alexander Trautsch
- Benjamin Ledel
- Alireza Aghamohammadi
- Taher Ahmed Ghaleb
- Kuljit Kaur Chahal
- Tim Bossenmaier
- Bhaveet Nagaria
- Philip Makedonski
- Matin Nili Ahmadabadi
- Kristof Szabados
- Helge Spieker
- Matej Madeja
- Nathaniel Hoy
- Valentina Lenarduzzi
- Shangwen Wang
- Gema Rodríguez-Pérez
- Ricardo Colomo-Palacios 
- Roberto Verdecchia
- Paramvir Singh
- Yihao Qin
- Debasish Chakroborti
- Willard Davis
- Vijay Walunj
- Hongjun Wu
- Diego Marcilio
- Omar Alam
- Abdullah Aldaeej
- Idan Amit
- Burak Turhan
- Simon Eismann
- anna
- Ivano Malavolta
- Matus Sulir
- Fatemeh Fard
- Austin Z. Henley
- Stratos Kourtzanidis
- Eray Tuzun
- Christoph Treude
- Simin Maleki Shamasbi
- Ivan Pashchenko
- Marvin Wyrich
- James Davis
- Alexander Serebrenik
- Ella Albrecht
- Ethem Utku Aktas
- Daniel Strüber
- Johannes Erbel

date: "2021"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Empricial Software Engineering*
publication_short: In *ESEM*

abstract:  Context Tangled commits are changes to software that address multiple concerns at once. For researchers interested in bugs, tangled commits mean that they actually study not only bugs, but also other concerns irrelevant for the study of bugs.**Objective** We want to improve our understanding of the prevalence of tangling and the types of changes that are tangled within bug fixing commits. **Methods** We use a crowd sourcing approach for manual labeling to validate which changes contribute to bug fixes for each line in bug fixing commits. Each line is labeled by four participants. If at least three participants agree on the same label, we have consensus. **Results** We estimate that between 17% and 32% of all changes in bug fixing commits modify the source code to fix the underlying problem. However, when we only consider changes to the production code files this ratio increases to 66% to 87%. We find that about 11% of lines are hard to label leading to active disagreements between participants. Due to confirmed tangling and the uncertainty in our data, we estimate that 3% to 47% of data is noisy without manual untangling, depending on the use case.**Conclusion** Tangled commits have a high prevalence in bug fixes and can lead to a large amount of noise in the data. Prior research indicates that this noise may alter results. As researchers, we should be skeptics and assume that unvalidated data is likely very noisy, until proven otherwise.  

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [tangled changes, tangled commits, bug fix, maual validation, research turk, registered report]

# Display this page in the Featured widget?
featured: false 

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2011.06244.pdf'
url_code: 'https://github.com/sherbold/replication-kit-2020-line-validation'
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
