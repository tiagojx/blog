+++
draft = true
date = '{{ .Date }}'
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
terminal_title = '{{ printf "%s.md" .File.ContentBaseName }}'
author = 'Tiago Xavier'
+++
