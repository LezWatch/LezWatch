---
title: Administration - Documentation
permalink: /admin/documentation/
toc: true
sidebar:
  nav: "admin"
---

That would be this site. It's powered by Jekyll. The basic flow is to add a markdown page to the repository and it will automagically rebuild.

## Content

Everything is written in [Kramdown markdown](https://kramdown.gettalong.org/syntax.html) with YAML headers. If you don't know what that means, just copy an existing post. It's pretty straight forward.

### Headers

The YAML header is what tells Jekyll what to do when generating a post.

A sample header is as follows:

```
---
title: POST TITLE
permalink: /example/post-name/
toc: true
sidebar:
  nav: "[admin|writing]"
---
```

### Structure

Content lives in three places:

* `_pages` - Individual pages
* `_administration` - Docs on administration
* `_writing` - Docs on writing content


## Menus

The sidebar and navigation menus are controlled by `_data/navigation.yml` 
