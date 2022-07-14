---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
lastmod: {{ .Lastmod }}
githash: {{ .GitInfo.Hash }}
---