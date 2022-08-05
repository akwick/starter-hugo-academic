---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Talk: Go Flow Safe: Ensure Data Flow of your App with Taint Analyses@ GopherCon Europe"
event: "GopherCon Europe 2022"
event_url: "https://gophercon.eu"
location: "Berlin"
#address:
  #street:
  #city:
  #region:
  #postcode:
  #country:
#summary:
abstract: "Security vulnerabilities like SQL Injections may harm your application and static analyses like a taint analysis can help you to prevent these. In this talk, I will introduce the basic concepts of a taint analysis and how to configure and run the taint analysis Go Flow Leeve for Go."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2022-07-31T14:25:00+02:00
date_end: 2022-07-31T14:55:00+02:00
all_day: true

# Schedule page publish date (NOT event date).
publishDate: 2022-07-10T21:56:12+02:00

authors: [anna]
tags: [security, golang, GopherConEU, SQLInjection, sensitive data, static analysis, taint analysis, talk]

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
url_slides: 202207_GopherConEU.pdf

url_code: https://github.com/akwick/taint-analysis-go-gopherconeu22 
url_pdf: 
url_video: 

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

![Anna on stage with the summary slide in the background](IMG_6715.JPG)

## My Thoughts about the Talk

<blockquote class="twitter-tweet" data-dnt="true"><p lang="en" dir="ltr">Some thoughts about my <a href="https://twitter.com/gopherconeu?ref_src=twsrc%5Etfw">@gopherconeu</a> talk today.<br>📄 Slides, code, and impressions are now available online: <a href="https://t.co/65DgbHjq9y">https://t.co/65DgbHjq9y</a> <br><br>📸 by my partner. <a href="https://twitter.com/hashtag/golang?src=hash&amp;ref_src=twsrc%5Etfw">#golang</a> <a href="https://twitter.com/hashtag/gopherconEU?src=hash&amp;ref_src=twsrc%5Etfw">#gopherconEU</a> <a href="https://t.co/Pw1HsPOVt6">pic.twitter.com/Pw1HsPOVt6</a></p>&mdash; Anna-Katharina Wickert @GophetConEU (@akwickert) <a href="https://twitter.com/akwickert/status/1553823903528665088?ref_src=twsrc%5Etfw">July 31, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Twitter Impressions of the Talk

<blockquote class="twitter-tweet" data-dnt="true"><p lang="en" dir="ltr">And now - <a href="https://twitter.com/akwickert?ref_src=twsrc%5Etfw">@akwickert</a>, keeping it safe in <a href="https://twitter.com/hashtag/golang?src=hash&amp;ref_src=twsrc%5Etfw">#golang</a>!<a href="https://twitter.com/hashtag/gopherconEU?src=hash&amp;ref_src=twsrc%5Etfw">#gopherconEU</a> <a href="https://t.co/FBNm4FDqBw">pic.twitter.com/FBNm4FDqBw</a></p>&mdash; GopherCon Europe (@gopherconeu) <a href="https://twitter.com/gopherconeu/status/1553722827571970050?ref_src=twsrc%5Etfw">July 31, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-dnt="true"><p lang="en" dir="ltr">Great talk <a href="https://twitter.com/akwickert?ref_src=twsrc%5Etfw">@akwickert</a> ✨✨ <a href="https://twitter.com/gopherconeu?ref_src=twsrc%5Etfw">@gopherconeu</a> <a href="https://twitter.com/hashtag/gopherconEU?src=hash&amp;ref_src=twsrc%5Etfw">#gopherconEU</a> <a href="https://t.co/0knjdk2GF5">pic.twitter.com/0knjdk2GF5</a></p>&mdash; Acyony (@bonekdecroche) <a href="https://twitter.com/bonekdecroche/status/1553731474167398400?ref_src=twsrc%5Etfw">July 31, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-dnt="true"><p lang="en" dir="ltr">Great talk by <a href="https://twitter.com/akwickert?ref_src=twsrc%5Etfw">@akwickert</a> ! I learned a lot about security, go, and new terminology too! <a href="https://t.co/OvxFJlpSjv">pic.twitter.com/OvxFJlpSjv</a></p>&mdash; Marian Montagnino (@mmontagnino) <a href="https://twitter.com/mmontagnino/status/1553731741046669312?ref_src=twsrc%5Etfw">July 31, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-dnt="true"><p lang="en" dir="ltr">Thank you <a href="https://twitter.com/akwickert?ref_src=twsrc%5Etfw">@akwickert</a> for the shout out to <a href="https://twitter.com/ecosia?ref_src=twsrc%5Etfw">@ecosia</a> at <a href="https://twitter.com/gopherconeu?ref_src=twsrc%5Etfw">@gopherconeu</a> ❤️ loving listening to your talk about static analysis. It&#39;s inspirational to see you achieving your speaker goals on stage 🚀🤩<a href="https://twitter.com/hashtag/gopherconEU?src=hash&amp;ref_src=twsrc%5Etfw">#gopherconEU</a> <a href="https://t.co/E2sfDRYJPH">pic.twitter.com/E2sfDRYJPH</a></p>&mdash; Jessica Greene (@sleepypioneer) <a href="https://twitter.com/sleepypioneer/status/1553722752095379457?ref_src=twsrc%5Etfw">July 31, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-dnt="true"><p lang="en" dir="ltr"><a href="https://twitter.com/akwickert?ref_src=twsrc%5Etfw">@akwickert</a> is here to talk to us about static analysis and taint analysis. Looking forward to this one! <a href="https://twitter.com/gopherconeu?ref_src=twsrc%5Etfw">@gopherconeu</a> <a href="https://t.co/jlBWlVnxf5">pic.twitter.com/jlBWlVnxf5</a></p>&mdash; the ol&#39; tea-leg (@tealeg) <a href="https://twitter.com/tealeg/status/1553721876861575168?ref_src=twsrc%5Etfw">July 31, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-dnt="true"><p lang="en" dir="ltr">Shout out to <a href="https://twitter.com/dgryski?ref_src=twsrc%5Etfw">@dgryski</a> during <a href="https://twitter.com/hashtag/gopherconEU?src=hash&amp;ref_src=twsrc%5Etfw">#gopherconEU</a> talk on taint analyses. <a href="https://t.co/LBtA4JE3T4">pic.twitter.com/LBtA4JE3T4</a></p>&mdash; Lili Cosic (@LiliCosic) <a href="https://twitter.com/LiliCosic/status/1553725764926935040?ref_src=twsrc%5Etfw">July 31, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-dnt="true"><p lang="en" dir="ltr">Love seeing <a href="https://twitter.com/dgryski?ref_src=twsrc%5Etfw">@dgryski</a> show up in a <a href="https://twitter.com/gopherconeu?ref_src=twsrc%5Etfw">@gopherconeu</a> talking being given by <a href="https://twitter.com/akwickert?ref_src=twsrc%5Etfw">@akwickert</a>. <a href="https://twitter.com/hashtag/golang?src=hash&amp;ref_src=twsrc%5Etfw">#golang</a> <a href="https://t.co/oaqU2XRtXD">pic.twitter.com/oaqU2XRtXD</a></p>&mdash; William (Bill) Kennedy (@goinggodotnet) <a href="https://twitter.com/goinggodotnet/status/1553725630767894534?ref_src=twsrc%5Etfw">July 31, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-dnt="true"><p lang="en" dir="ltr">Some great words about <a href="https://twitter.com/gopherconeu?ref_src=twsrc%5Etfw">@gopherconeu</a> and I am flattered to be included in your list of great talks. ☺️ <a href="https://t.co/8dYVVaaAvB">https://t.co/8dYVVaaAvB</a></p>&mdash; Anna-Katharina Wickert (@akwickert) <a href="https://twitter.com/akwickert/status/1555275848630009856?ref_src=twsrc%5Etfw">August 4, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>