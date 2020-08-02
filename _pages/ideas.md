---
layout: page
short_title: Ideas
title: Ideas (Tentatively for GSOC 2018)
permalink: /ideas
description: "Ideas for projects that we want to build at Coding Blocks"
---

These are the ideas we plan to work on in 2018.
We might get selected as an Org to Google Summer of Code
If that occurs, then this is the GSoC 2018 official Ideas List.

Please also take a look at existing projects. We might be revamping
or adding features to many of those projects during 2018 as well

**_NOTE_** : You can submit your own ideas too.


To submit your own ideas
make a *Pull Request* to [this github repo](https://github.com/coding-blocks/lab.codingblocks.com)
and adding your idea to the [**_ideas**](https://github.com/coding-blocks/lab.codingblocks.com/tree/gh-pages/_ideas) folder.




{% for idea in site.ideas %}
<h2 class="idea-link">  {{ idea.title }} </h2>
<a href="{{ idea.url }}"> Details </a>
<p>
{{ idea.excerpt }}
</p>
-------
{% endfor %}
