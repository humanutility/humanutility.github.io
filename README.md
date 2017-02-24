# Humanutility Blog

This repository contains the blog for the Human Utility project! It runs on [GitHub Pages](https://pages.github.com/) using [Jekyll](https://jekyllrb.com/).

## Starting the site

If you're using a Mac or Linux, go to the terminal and run:

```
script/server
```

If you're using a Windows machine, go the command prompt and run:

```
jekyll serve --watch
```

In both cases, you can open a new browser and head to http://0.0.0.0:4000 to see the site :sparkles: live :sparkles:.

## Writing posts

New posts are written in Markdown. To add a new post, create a new file under the _posts/_ folder. It should start with a date in the format of `YYYY-MM-DD-`, followed by any title you want.

Each post needs to start with some [frontmatter](https://jekyllrb.com/docs/frontmatter/), which is sort of like metadata describing the post. Each post should have the following keys:

* `title`, which is the title of the post
* `permalink`, which is the URL link. Typically this is the person's name being highlighted.
* `description`, which is a short description of the person being highlighted.
* `image`, which is an image of the person being highlighted.

For example, this might look like this:

```
---
title: Meet Loria—The First Person The Human Utility Ever Helped
permalink: /loria-detroit/
description: Meet Loria. The first person in Detroit The Human Utility ever helped with a water bill.
image: https://www.dropbox.com/s/k2i3ivenw1uobxi/loria.jpeg?dl=1
---
```

These metadata keys (`image`, `title`) are important, because they are used by the [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag) plugin to create cards for Twitter and Facebook.

## Plugins used

The following plugins are used to help make the site:

- [jekyll-feed](https://github.com/jekyll/jekyll-feed)
- [jekyll-sitemap](https://github.com/jekyll/jekyll-sitemap)
- [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag)
- [jemoji](https://github.com/jekyll/jemoji)

## TODO

* Fix header and footer so that they match the rest of the website
* A lot of the SCSS styles were just stolen from Stripe. The files in the *_sass/* folder should be reviewed to make sure they're actually being used.
* There should probably be shared on Twitter/Facebook buttons.
