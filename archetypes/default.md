---
date: '{{ .Date }}'
slug: '{{ replace .File.ContentBaseName "-" "-" | lower }}'
h1: '{{ replace .File.ContentBaseName "-" " " | title }}'
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
description: ''
keywords: ''
tariffStatus: ''
section: ''
shortname: ''
cover: ''
coverAlt: ''
leadtext: ''
---
