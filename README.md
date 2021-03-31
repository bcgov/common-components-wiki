[![img](https://img.shields.io/badge/Lifecycle-Retired-d45500)](https://github.com/bcgov/repomountie/blob/master/doc/lifecycle-badges.md)

# GitHub Pages Test

A basic GitHub Pages site built using Jekyll and Markdown via kramdown.

## Table of Contents

1. [Getting Help or Reporting an Issue](#getting-help-or-reporting-an-issue)
1. [How to Contribute](#how-to-contribute)
1. [Installation](#installation)
1. [Editing](#editing-site-content)
1. [License](#license)

## Getting Help or Reporting an Issue

To report bugs/issues/feature requests, please file an [issue](https://github.com/bcgov/common-components-wiki/issues).

## How to Contribute

If you would like to contribute, please see our [contributing](CONTRIBUTING.md) guidelines.

Please note that this project is released with a [Contributor Code of Conduct](CODE-OF-CONDUCT.md). By participating in this project you agree to abide by its terms.

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

## License

    Copyright 2020 Province of British Columbia

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
