---
title: Home
sections:
  - component: HeroBlock
    content: >-
      This section can contain a subtitle or tagline. The recommended length is
      one to three sentences, but can be changed as you prefer. lol
    section_id: hero
    type: heroblock
  - actions:
      - label: Contact Me
        url: /contact
    component: ContentBlock
    content: >-
      This is the "about" excerpt. It can be used to provide a paragraph about
      yourself that people can read on the homepage to get a sense of who you
      are. There also exists a dedicated about page where you can write more
      about yourself for those who are interested.
    section_id: about
    title: About
    type: contentblock
  - actions:
      - label: View Blog
        url: blog/index.html
    component: PostsBlock
    num_posts_displayed: 4
    section_id: recent-posts
    title: Recent Posts
    type: postsblock
menus:
  main:
    title: Home
    weight: 1
template: home
---

