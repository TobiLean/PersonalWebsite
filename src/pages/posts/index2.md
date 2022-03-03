---
title: Hello world!
publishDate: 12 Sep 2021
author: Nate Moore
authorURL: https://github.com/natemoo-re
heroImage: /assets/blog/introducing-astro.jpg
value: 128
description: Just a Hello World Post!
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Components from '../../components'
  const { Author } = Components
---

<Author name="Nate Moore" href="https://twitter.com/n_moore" />

This is so cool!

Do variables work {frontmatter.value * 2}?
