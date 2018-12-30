---
title: "Plants"
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.2"
  overlay_image: https://dl.airtable.com/5QREFPhhSAq3w4rQbO6G_full_2018-05-31%2021.46.01.jpg
  actions:
    - label: "Care Guide"
      url: "/plants.html"
excerpt: "Final project, involving Ruby, Airtable, Jekyll, and plants."

---

This project combines [Jekyll](https://jekyllrb.com/) + [Airtable](https://airtable.com/).

Airtable is a relational database that is basically a sexier, more powerful version of Google sheets that is great for storing and organizing almost anything. So what if you want to share your Airtable base with the world... _and_ make it attractive?

In this exercise, I'm using Airtable as an easy content management system for Jekyll in addition to Jekyll's built-in blogs function. This allows anyone with access to the base to edit or add records, and those changes will automatically appear on the site.

This [Plants Airtable Base](https://airtable.com/shrkyrmwA7q05dfqp) tracks care instructions for a small collection of houseplants.

The [Plant Care Guide]({{ site.url }}/plants/) section of this site automatically generates one page per record in this base via a few custom plugins.
