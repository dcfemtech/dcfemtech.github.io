# [DCFemTech Website](http://dcfemtech.github.io)

## Development
This site uses [Jekyll](http://jekyllrb.com/) and hosts on Github pages.

If you don't have bundler:
- `gem install bundler`
Then:
- `bundle install`
- `bundle exec jekyll serve`

## Redirect
We've added in the [Jekyll Redirect Gem](https://github.com/jekyll/jekyll-redirect-from) to handle redirects from old URL's. To use it, just add the url that you want to redirect to the page into the page frontmatter:
ie:

```
---
layout: default
redirect_from:
  - /dcftawards_2016
---
```

## Adding Organizations

## Adding more Events that will communicate with us 
