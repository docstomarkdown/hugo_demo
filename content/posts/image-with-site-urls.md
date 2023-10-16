---
title: "image-post-with-variables"
date: 2022-11-20T09:03:20-08:00
draft: false
slug: image-post-with-variables
---
# This post is to demonstrate images in Markdown

Thisa


## Subheading 1
<!-- Base URL: {{ .Site.BaseURL }} -->

![alt text]({{ .Site.BaseURL }}/images/image_1.jpg)

using the global site.Baseurl

![alt text]({{ site.BaseURL }}/images/image_1.jpg)

Image will be displayed from GitHub
