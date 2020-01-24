# GitHub Pages Test

A basic GitHub Pages site built using Jekyll and Markdown via kramdown.

## Installation

Ensure ruby and homebrew are installed. Out of the scope of these instructions.

Install bundler, a dependency manager for Ruby gems.

`gem install bundler`

Navigate to project directory and install dependencies using bundler.

`bundle install`

The above command install dependencies listed in the *Gemfile*. Minimum dependencies are included for this demonstration.

To serve the site locally, run `bundle exec jekyll serve`. The site should now be accessible via [localhost:4000](http://localhost:4000).

## Editing Site Content

Create new Markdown files in the pages directory. Pages consist of standard Markdown save for a small section at the top defining the pages layout, indexing, and place within the site structure. This is called the YAML front matter.

Add a title, etc. to the front matter as bellow.

```
layout: default
title: Child
parent: Parent
nav_order: 2
```

Commit changes and push.

```
git add -A
git commit -m "Your commit message here"
git push
```

That's it, you're done!
