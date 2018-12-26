---
title: Writing Content - Shortcodes
permalink: /writing/shortcodes/
toc: true
sidebar:
  nav: "writing"
---

We have a number of shortcodes available however most have been converted to [blocks](/writing/block-editor/). The following remain for use inside other blocks.

## Badges

Insert Bootstrap badge code as a shortcode not HTML

Usage: `[badge url="LINK" class="class class" role="role"]TEXT[/badge]`

## Copyright Year

Usage: `[copyright year=(start year) text=(copyright text)]`

Attributes:

* year = (int) start year. (default: current year)
* text = (text) copyright message. (default: &copy; )

## Number of Posts via shortcodes

Usage: `[numposts data="posts" posttype="post type" term="term slug" taxonomy="taxonomy slug"]`

Attributes:

* data = `[posts|taxonomy]`
* posttype = post type
* term = term slug
* taxonomy = taxonomy slug

## This Month

_Deprecated_: We don't use this anymore.

Display This Month recap of characters and shows added

Usage: `[thismonth]` or `[thismonth date="2017-01"]`

Outputs UL list:

 * X shows added
 * X characters added
