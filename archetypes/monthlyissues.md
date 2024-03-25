+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
draft = true
layout = 'monthlyissue'
folder = '{{ replace .File.ContentBaseName "-" " " | title }}'
volume = 1
issue = 1
+++
