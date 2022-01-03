---
title: Research Papers
description: |
 Here you can find out about my research and published papers. 
author: "Abdul M Khan"
show_post_thumbnail: true
show_author_byline: true
show_post_date: true
show_post_time: true
# for listing page layout
layout: list-sidebar # list, list-sidebar, list-grid

# for list-sidebar layout
sidebar: 
  title: Research papers
  description: |
    Here you can find out about my research and published papers.
    
    Check out the _index.md file in the /talk folder 
    to edit this content. 
  author: "Abdul M Khan"
  text_link_label: Subscribe via RSS
  text_link_url: /index.xml
  show_sidebar_adunit: true # show ad container

# set up common front matter for all pages inside blog/
cascade:
  author: "The R Markdown Team @RStudio"
  show_author_byline: true
  show_post_date: true
  show_post_time: true
  show_disqus_comments: false # see disqusShortname in site config
  # for single-sidebar layout
  sidebar:
    text_link_label: View recent talks
    text_link_url: /talk/
    show_sidebar_adunit: false # show ad container
---

** No content below YAML for the talk _index. This file provides front matter for the listing page layout and sidebar content. It is also a branch bundle, and all settings under `cascade` provide front matter for all pages inside talk/. You may still override any of these by changing them in a page's front matter.**