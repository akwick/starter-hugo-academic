---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Crypto Fails and How to Tackle Them in Go @ GoDevNet"
event: "GoDevNet: Glorious Go Gals - a collection of wonderful women talking about their work in Go."
event_url: "https://www.meetup.com/gobridge/events/277830571/"
location: "Online [Meetup]"
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "Recent studies in academia and industry [1-3] reveal that the (vast) majority of applications using crypto struggle with a functional and secure solution. Because of these struggles, the application ends up with attackable components, e.g., passwords stored insecurely. Further, these issues can lead to messages like “Our application is secure as it uses the standard AES-128.” However, it is easily attackable as the wrong parameters for the AES encryption were chosen.

In this talk, we will introduce and explain six very frequently discussed problems for insecure crypto usages and demonstrate secure solutions for common use cases. We will start by understanding why these six issues are a security problem without using any mathematical formula at all. After knowing why we should avoid these mistakes in our application, we take a look at the standard Go crypto library and inspect if we can repeat finding these issues in implementations using this library as well. A small spoiler: You can’t repeat all due to the design decisions of the Go API. However, you can find issues and discussions about why Go shouldn’t support these insecure solutions as well. We will end the talk with code examples of common tasks involving crypto and shortly demonstrate how static analyses can help you implement a secure solution."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2021-05-21T17:00:00-05:00
# date_end: 2022-05-16T21:56:12+02:00
all_day: true

# Schedule page publish date (NOT event date).
publishDate: 2022-05-16T21:56:12+02:00

authors: [anna]
tags: [crypto, golang, API-misuse, talk]

# Is this a featured event? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your event's folder or a URL.
url_slides:

url_code: "https://github.com/akwick/crypto-go"
url_pdf: "https://github.com/akwick/crypto-go/blob/master/20200521_Crypto-Fails-and-how-to-tackle-them-in-go.pdf"
url_video: "https://www.youtube.com/watch?v=IsjZk5ruqzY"

# Markdown Slides (optional).
#   Associate this event with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
