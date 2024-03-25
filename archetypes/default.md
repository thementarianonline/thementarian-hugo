+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
author = "name"
draft = true
categories = [""]
slug = "{{ replace .File.ContentBaseName "-" " " | title }}"
+++
