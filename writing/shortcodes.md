---
layout: default
title: Writing Content - Shortcodes
permalink: /writing/shortcodes/
---

A list of shortcodes available on LezWatch.TV

## Author Box

Usage: `[author-box users=username]`

## Badges

Insert Bootstrap badge code as a shortcode not HTML

Usage: `[badge url=LINK class="class class" role="role"]TEXT[/badge]`

## Copyright Year

Usage: `[copyright year=(start year) text=(copyright text)]`

Attributes:
* year = (int) start year. (default: current year)
* text = (text) copyright message. (default: &copy; )

## Glossary

Show Category Icons used for taxonomies.

Usage: `[glossary taxonomy=TAXONOMY]`

## Number of Posts via shortcodes

Usage: `[numposts data="posts" posttype="post type" term="term slug" taxonomy="taxonomy slug"]`

Attributes:
* data = `[posts|taxonomy]`
* posttype = post type
* term = term slug
* taxonomy = taxonomy slug

## Screeners

Usage: `[screener title="Some Like It Hot" summary="A quirky black and white romcom" queer="2" worth="yes" trigger="low"]`

Attributes:
 * title = Title of show (required - defaults to "TBD")
 * summary = 140 characters of summary (required - defaults to "coming soon")
 * queer = a number, 0-5, reflecting how good it is for queers (required - defaults to 3)
 * worth = `[yes|no|meh]` (required - defaults to meh)
 * trigger = `[low|medium|high]` (optional - defaults to 'none' which shows nothing)

## Spoilers

Usage: `[spoilers]` or `[spoilers warning="OMG SPIDERS!!!"]`

## This Month

_Deprecated_: We don't use this anymore.

Display This Month recap of characters and shows added

Usage: `[thismonth]` or `[thismonth date="2017-01"]`

Outputs UL list:
 * X shows added
 * X characters added
