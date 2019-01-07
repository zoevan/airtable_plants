# airtable_plants 🌿
A plant-themed exercise of integrating Airtable with a Jekyll site. Final project for intro to programming class.

https://morning-chamber-80661.herokuapp.com/plants.html




This project combines [Jekyll](https://jekyllrb.com/) + [Airtable](https://airtable.com/).

Airtable is a relational database that is basically a sexier, more powerful version of Google sheets that is great for storing and organizing almost anything. So what if you want to share your Airtable base contents... _and_ make it attractive and non-spreadsheety?

In this exercise, I'm using Airtable as a content management system for Jekyll in addition to Jekyll's built-in blogs function.

This [Plants Airtable Base](https://airtable.com/shrkyrmwA7q05dfqp) tracks care instructions for a small collection of houseplants. (I like plants.)

The Plant Care Guide section of [this site](https://morning-chamber-80661.herokuapp.com/plants.html) automatically generates one page per record in this base via a few custom plugins based on [these Jekyll-Airtable utilities](https://github.com/calebhicks/jekyll-airtable-utilities).

# Overview:
- The Airtable API Key is stored as a config variable in the `.env` file (added to `.gitignore`) and config variables were added directly to Heroku for deployment.
- Settings `_config.yml` dictate which Airtable tables/views are pulled and where pages are generated.
- The `airtable_fetcher.rb` plugin generates a JSON file with the record data in the `_data` folder.
- The `airtable_page_generator.rb` plugin generates pages from each record pulled from Airtable, using the `plants.html` layout.
- Theme is [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes)
