This repository contains the source for <http://verilogtorouting.org>

The pages are generated using [Jekyll](https://jekyllrb.com/).
All pages are written in [Markdown](https://en.wikipedia.org/wiki/Markdown) and converted into HTML by Jekyll.

The actual webpage is hosted by GitHub (verilog-to-routing.github.io) with a custom domain (verilogtorouting.org).
GitHub automatically runs Jekyll to regenerate the website whenever a commit is push to the repository.

Organization
============

* `index.md`  - The main page

* `_config.yml` - Jekyll configuration file
* `Gemfile, Gemfile.lock` - Defines tool vesions used to build the site
* `img` - Directory containing images
* `_includes` - Directory containing html fragments 'included' into pages by Jekyll (e.g. Header, Footer)
* `_pages` - Directory containing *.md files defining stand-alone pages
* `_posts` - Directory for blog posts (currently unused)
* `_site` - Build directory created by Jekyll
* `CNAME` - Defines the custom domain (used by GitHub)

Modifying the Website
=====================

Modifying an existing page
--------------------------
Simply edit the associated *.md file, commit the change and push it to GitHub.

Adding a new page
--------------------------
Add the new Markdown file (e.g. `mynewpage.md`) to the `_pages` directory.

Ensure the top of the file contains the following:
```
---
layout: page
title: <title>
permalink: /<link>/
---
```

Where `<title>` is replaced with the title of the page (e.g. `My New Page`), and `<link>` is replaced with the page URL (e.g. if `<link>` is `mynewpage` the new page will be served at `verilogtorouting.org/mynewpage`).

New pages will be automatically added to the header navigation bar by Jekyll (see `_includes/header.html`).

Building Locally
================
It is useful to test changes locally before pushing to GitHub.

See [here](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/) for details on installing Jekyll with a configuration to match GitHub's.

Once complete you can run
```
bundle exec jekyll serve
```
Which will start a local server (e.g. http://127.0.0.1:4000/) you can connect to with a browser to preview your changes.
