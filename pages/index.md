---
layout: page
title: Fransgenre WIKI
permalink: /
---

# Bienvenue sur le wiki

Ce wiki à pour but de centraliser les ressources et d'informer quant à la transidentité

## Comment participer ?

Je vous invite à consulter le [wiki](https://github.com/fransgenre/fransgenre.github.io/wiki) disponible sur Github.

Collection_dir: "{{ site.collections_dir }}"

Page.collection: "{{ page.collection }}"

{% if !page.collection %}{{ site.collections_dir }}{% endif %}

