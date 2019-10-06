---
title: Home
sections:
  - section_id: hero
    component: hero_block.html
    type: heroblock
    content: >-
      I am a software developer with a blog. How cliché.
  - section_id: about
    component: content_block.html
    type: contentblock
    title: About
    content: >-
      Technically, this is not a blog - it's a collection of my posts from [DEV](https://dev.to). 
    actions:
      - label: Contact Me
        url: /contact
  - section_id: recent-posts
    component: posts_block.html
    type: postsblock
    title: Recent Posts
    num_posts_displayed: 4
    actions:
      - label: View Blog
        url: blog/index.html
layout: home
menu:
  main:
    weight: 1
    name: Home
---
