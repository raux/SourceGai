---
title: "Ipsum"
description: ""
slug: "ipsum"
image: pic10.jpg
keywords: ""
categories: 
    - "testing"
    - "testing"
date: 2017-10-31T21:28:43-05:00
draft: false
---

This is a test 

{{ range .Site.Data.johnpatitucci}}
   {{ partial "artist.html" . }}
{{ end }}




