# Jekyll-Paper
*Based on: [Jekyll-Paper](https://github.com/ghosind/Jekyll-Paper).*

## Features

- RSS
- Sitemap
- Custom 404 page
- SASS
- Internationalization
- Configurable navigation menu
- Categories Index
- SEO optimization
- Mathematics (MathJax)
- Diagrams (Mermaid)
- Comments (Disqus)

## Getting Start

Jekyll Paper is easy to create your own blog. You can create your blog by five steps only!

1. `$ gem install bundler jekyll`
2. `$ git clone git@github.com:ghosind/Jekyll-Paper.git`
3. `$ cd Jekyll-Paper`
4. `Jekyll-Paper $ bundle install`
5. `Jekyll-Paper $ bundle exec jekyll serve`

## Custom Navigation Menu

You can add or update navigation menu items in `_data/menus.yml` file. In the configuration file, you need set title and URL for every navigation menu item.

### Example

```yml
- title: "Index"
  url:   ""

- title: "Github"
  absoluteUrl: true
  url: "https://github.com/john_doe"

- title: "About"
  url:   "about"
```
