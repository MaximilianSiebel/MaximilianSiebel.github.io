---
layout: page
permalink: /publications/
title: Publications
description: Journal articles, preprints, and doctoral thesis.
nav: true
nav_order: 3
---

<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}">

{% include bib_search.liquid %}

<div class="publications" markdown="1">

## Peer-reviewed publications

{% bibliography --query @*[status=published] --group_by none %}

## Preprints

{% bibliography --query @*[status=preprint] --group_by none %}

## Doctoral thesis

{% bibliography --query @*[status=thesis] --group_by none %}

</div>
