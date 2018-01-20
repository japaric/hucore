+++
author = "John Smith"
date = {{ .Date }}
draft = true
tags = ["a", "b", "c"]
title = "{{ replace .TranslationBaseName "-" " " | title }}"
+++
