---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A new website - Markdown"
subtitle: ""
summary: "A post in Markdown"
authors: ["Sebastiaan de Klerk"]
tags: []
categories: []
date: 2020-05-07T13:34:26+02:00
lastmod: 2020-05-07T13:34:26+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  placement: 1
  caption: "Markdown"
  focal_point: "center"
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
This website has been created using RStudio, specifically the Blogdown package, that 
can be installed in R using the following piece of code:
```r
install.packages("blogdown")
```
The package can be loaded in the RStudio global environment by using:
```r
library(blogdown)
```
The nice thing about building websites in R is that the text can be made up in Mmarkdown,
which allows you to present code, as seen above. You can also give commments with the code,
like this:
```r
1 + 1 # not executed
```
It is important to note that there are two types of Markdown. The regular Markdown does not
allow any execution of code, while R Markdown does allow execution of code. For example,
this post has been written in Markdown, and therefore 1 + 1 will not be calculated.
Based on what you want to display on the website, it is important to decide which type
of Markdown to use.

This website is hosted by Netlify, and the files that make up this website are available on
my GitHub account (https://www.github.com/Sebastiaan1986). The website is powered by
the Academic theme for Hugo.












