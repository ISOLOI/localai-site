---
layout: blog.njk
title: Articles
metaDescription: ""
date: 2017-01-01
permalink: blog{% if pagination.pageNumber > 0 %}/page/{{ pagination.pageNumber
  }}{% endif %}/index.html
subtitle: A collection of technical blog posts and random thoughts
eleventyNavigation:
  key: Blog
  order: 2
pagination:
  data: collections.post
  size: 20
---
p﻿oats to read...