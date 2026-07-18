source for my personal blog, [georgenixon.co.uk](http://georgenixon.co.uk). it's a [Jekyll](https://jekyllrb.com/) site using the [minima](https://github.com/jekyll/minima) theme, built and served by GitHub Pages.

## running locally

```
bundle install
bundle exec jekyll serve
```

## posting

drop a new file in `_posts/`, named `YYYY-MM-DD-title.md`, with front matter like:

```
---
layout: post
title: "Title"
date: YYYY-MM-DD HH:MM:SS +0100
---
```

