---
title: Writing Content
permalink: /admin/assets/
toc: true
sidebar:
  nav: "admin"
---

A list of WP-CLI commands available on LezWatch.TV

If you don't use shell access to the site, you can ignore this.

## Calculations

Re-run any calculation generations

* `wp lwtv calc show [ID]` Re-runs show calculations
* `wp lwtv calc actor [ID]` Re-runs counts of characters

## Find

Find post content missing specific flags.

### Queerchars

* `wp lwtv find queerchars`

This command will list all characters flagged as queer-irl _without_ any actors who are queer, as well as any characters _not_ marked queer when they have at least one queer actor.
