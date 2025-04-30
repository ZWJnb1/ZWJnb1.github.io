---
title: "{{ replace .Name "-" " " | title }}" # 自动生成标题
date: {{ .Date }} # 自动生成日期
draft: false
cover:
  image: "/images/default.jpg" # 默认封面图片路径，可修改
summary: "这里是文章简介，请填写内容。" # 默认简介
---
