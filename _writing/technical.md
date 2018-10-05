---
title: Writing Content - Technical Stuff
permalink: /writing/technical/
toc: true
sidebar:
  nav: "writing"
---

This is mostly here to keep us organized. For the most part, editors won't have to worry about this.

## Custom Post Types and Taxonomies

There are three custom post types (CPTs) on this site: TV Shows, Actors, and Characters. They make up the database.

Each post type represents one item. So a TV Show CPT is an individual show, and so on. In addition, each post type has a number of custom taxonomies to be used to organize data.

### Taxonomies per post type

* TV Shows: TV Stations, Tropes`*`, Formats`*`, Genres`*`, Nations, Stars, Triggers, Intersections`*`
* Actors: Genders, Sexualitys
* Characters: Cliches`*`, Genders, Sexual Orientation, and Romantic Orientation

These fields either auto complete or are selectable via dropdowns.

If you need to add a new Nation or Station, you can do so via the post editor. If you need to add in more genders or romantic orientations, you will need to edit the taxonomy (available via the menu).

Keep in mind, certain taxonomies (indicated with a `*`) use symbolicons (see below). They also shouldn't be added too all that often. If you need help, grab Mika.

### Symbolicons

Ahhhh. Symbolicons. The basic idea was to add in pretty, cool, pictures to all the taxonomies and have them cross link back and forth to the show and character pages. In order to do this, some pretty weird code was written into the theme.

In order to force things properly, you cannot add to certain taxonomies from the post editor. The only one you can is for TV Stations. Everything else has to be managed via the taxonomy editor for a reason. When you add a new item to the taxonomy, you have to add in a symbolic icon (see? symbolicon) from the dropdown menu.
