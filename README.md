# template-candidate-site
A forkable template for Jekyll to easily generate candidate sites whomst need them.

# Installing Jekyll #
This project is built upon Jekyll, the Ruby based static site generator. You can get instructions to install it [here](https://jekyllrb.com/docs/installation/)

# I don't know Ruby! #
I barely know any Ruby; it's really only used for custom plugins which aren't available on GH pages anyway. Jekyll is mostly templating and data structure building. The templating language is [Liquid](https://shopify.github.io/liquid/). There is also Jekyll specific documentation [here](http://jekyllrb.com/docs/liquid/). The rest is just html, javascript and css.

# Getting Started #
Clone this repo to your favorite working directory, and if Jekyll is installed already, you should be able to just run `jekyll serve` to start the server. If it encounters errors, you may need to run `bundle install` first. `jekyll serve --watch` sets up the server in a persistent, auto-updating state, where changes are regenerated automatically and errors will be spat to stdout.

# Jekyll Admin #
~~I just learned about and started using this, so I'm getting the hang of it. If you visit http://localhost:3000/admin it will enter into a UI where content can be managed, data can be entered, and files can be uploaded.~~
Currently disabled for the repo. It works nicely, but is using older libraries that are insecure, so it doesn't need to be part of the repo.
