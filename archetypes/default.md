+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ time.Format "2 January 2006" .Date }}
author = "name"
categories = [""]
slug = "{{ replace .File.ContentBaseName "-" " " | title }}"
+++
