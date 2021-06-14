---
layout: single
title: Contributing
permalink: /contributing/
---

## Contributing to this project

This page is built with Jekyll. You'll need to install Ruby and Bundler. Fork the [recipl.es repo](https://github.com/reciples/reciples.github.io), go to the directory and run `bundle install`. Once it's completed, start the server with `bundle exec jekyll serve`. You are good to test locally! 

Make a copy of the Recipe Template (or _recipl templ_, for short), located [here](/recipltempl), and create a new post with it under the `_posts` folder. Write up the ingredients, processes, comments, etc. Add pictures if you like. Please use the following pattern for the post file name: `YYY-MM-DD-Name.md`.

Next, go to `_data` and edit `authors.yml` to add information about you. You can also post anonymously. In your post, just make sure the `author` key matches exactly the entry you declared at `authors.yml`.

Make sure the server runs locally and incorporates your changes, then submit a pull request, so we can all enjoy your fantastic reciPLes! 

