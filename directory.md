---
layout: page
title: The Directory
permalink: /directory
---

A more comprehensive directory has been compiled and is crowdsourced at our sister website: [chocodex.net](https://chocodex.net).  The manual directory below is our old directory which we're keeping here for posterity and nostalgia.

|Name | Primary Location | Countries with Locations | Shipping Destinations | Main Chocolate Types | Interesting Chocolate | Sells Confections | Sells Bulk (e.g. for baking) | Why it's notable | Last Updated | Notes|
|--------|-------|-------|-------|-------|-------|-------|-------|-------|-------|------|
{% for maker in site.data.directory %}|{{ maker.name }}|{{ make.primary_location }}|{{ maker.locations }}|{{ maker.shipping }}|{{ maker.chocolate_types }}|{{ maker.interesting_chocolate }}|{{ maker.sells_confections }}|{{ maker.sells_bulk }}|{{ maker.notable }}|{{ maker.updated_at }}|{{ maker.notes }}|
{% endfor %}
