---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Aggregating PDFs with a One-Line Bash Script"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2020-05-05T01:00:56-05:00
lastmod: 2020-05-05T00:28:56-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

This year, like dozens of Canadian researchers, I'm serving on a SSHRC Insight Development Grant selection committee. While SSHRC has a decent back end (I think I'm one of the only people who kinda likes SharePoint now), they do tend to provide the documents that need to be reviewed in a bunch of seperate documents, i.e.:

* `App_Milligan_Ian.pdf`
* `Attach_Milligan_Ian_Description.pdf`
* `Attach_Milligan_Ian_References.pdf`
* `Attach_Milligan_Ian_Timelines.pdf`
* `CCV_App_Milligan_Ian.pdf`

Scale this up by the 11 or 12 proposals that you need to read, and suddenly, you're working with 60 individual PDFs rather than just 12 nicely-packaged PDFs. As somebody who tends to move PDFs to my iPad to annotate there, this is a bit annoying.

This isn't just a SSHRC problem, of course. Until a few years ago, when reviewing graduate admissions, we would get four of five PDFs per applicant.

Bash to the rescue. This MacOS command will turn all of the above into a nice PDF for review:

```bash
"/System/Library/Automator/Combine PDF Pages.action/Contents/Resources/join.py" -o Milligan.pdf *Milligan*
```

This saved me a lot of headache, so maybe if it saves just one of you some headache, posting it here will be worth it too. 