---
layout: archive
title: "Open Positions"
permalink: /positions/
author_profile: true
---

{% include base_path %}

* I currently have an open postdoc position to work on Internal Tide dynamics, with a focus on data assimilation for Internal Tide estimate from observations (including SWOT data). 
A description of the position is given [here][postdoc_modito], and feel free to [contact](/Contact) me if you are interested or want further informations.
* There are regularly some open positions in the Odyssey team, which are usually advertised on the [website](https://team.inria.fr/odyssey/)

[postdoc_modito]: {{ base_path }}/positions/postdoc_modito/

essai [ici](/positions/postdoc_modito.md)

{% for post in site.positions reversed %} {% include archive-single.html %} {% endfor %}
