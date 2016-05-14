---
layout: post
title: "Use Select to Get Array of Collection Subset"
author: me
modified:
excerpt: "test post"
tags: []
---

One of the biggest and easiest improvements to my code in my first year as a RoR developer was incorporating the widespread use of select.

In my earlier days of Ruby, I often found myself creating an new empty array, then iterating through an Active Record collection (or simple array) with a block that pushed elements into that new array if it met certain conditions. This approach works and is pretty straightforward, but is much more verbose than using select.

