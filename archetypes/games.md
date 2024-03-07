+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ now.Format "2006-01-02" }}
tags = [tag1, tag2, tag3, tag4]
image = '{{ .Site.BaseURL }}1.png'
description = '{{ replace .File.ContentBaseName "-" " " | title }}'
+++
