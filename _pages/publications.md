---
layout: page
permalink: /publications/
title: publications
description: Publications and preprints in reverse chronological order.
nav: true
nav_order: 3
---

{% include bib_search.liquid %}

## Peer-reviewed publications

{% bibliography --query @*[status=published] --group_by none %}

## Preprints

{% bibliography --query @*[status=preprint] --group_by none %}