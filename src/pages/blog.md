---
layout: blog.njk
title: Articles
date: 2024-12-31
pagination:
  data: collections.post
  size: 20
permalink: "blog{% if pagination.pageNumber > 0 %}/page/{{ pagination.pageNumber }}{% endif %}/index.html"
metaDescription: A sample Blog page listing various posts.
subtitle: A collection of technical blog posts and random thoughts
eleventyNavigation: false
# eleventyNavigation:
  # key: Blog
  # order: 2
  # hide: true
---
