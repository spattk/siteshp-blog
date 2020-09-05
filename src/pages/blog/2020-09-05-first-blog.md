---
templateKey: blog-post
title: First Blog
date: 2020-09-05T04:24:07.945Z
description: Hey there, how are you doing.
featuredpost: false
featuredimage: /img/apple-touch-icon.png
tags:
  - python
---


1. import **openpyxl**.
2. wb = **openpyxl**.load_workbook('sample_file.xlsx')
3. sheet = wb.active.
4. x1 = sheet\['A1']
5. x2 = sheet\['A2']
6. \#**using cell**() function.
7. x3 = sheet.**cell**(**row**=3, **column**=1)
8. print("The first **cell** value:",x1.value)