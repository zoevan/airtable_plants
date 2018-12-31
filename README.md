# airtable_plants
A plant-themed exercise of integrating Airtable with a Jekyll site.
https://morning-chamber-80661.herokuapp.com/plants.html

--------------------

This project combines [Jekyll](https://jekyllrb.com/) + [Airtable](https://airtable.com/).

Airtable is a relational database that is basically a sexier, more powerful version of Google sheets that is great for storing and organizing almost anything. So what if you want to share your Airtable base with the world... _and_ make it attractive?

In this exercise, I'm using Airtable as a content management system for Jekyll in addition to Jekyll's built-in blogs function.

This [Plants Airtable Base](https://airtable.com/shrkyrmwA7q05dfqp) tracks care instructions for a small collection of houseplants.

The Plant Care Guide section of [this site](https://morning-chamber-80661.herokuapp.com/plants.html) automatically generates one page per record in this base via a few custom plugins based on [these Jekyll-Airtable utilities](https://github.com/calebhicks/jekyll-airtable-utilities).

The Airtable API Key is stored in an `.env` file that is not uploaded to GitHub. The config variable for the API Key was then added to Heroku.
