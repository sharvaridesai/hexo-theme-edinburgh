# Edinburgh

Edinburgh is a clean, beautiful, and responsive portfolio theme for the Hexo static site generator. View a demo of the theme [here](https://sharvaridesai.github.io/hexo-theme-edinburgh-demo/).

![Screenshot of Edinburgh theme](https://sharvaridesai.github.io/hexo-theme-edinburgh-demo/images/screenshot.png)

### Theme installation
From the root directory of your Hugo site, run the following command:
```
$ git clone https://github.com/sharvaridesai/hexo-theme-edinburgh themes/edinburgh
```
Then update your blog's main `_config.yml` to set the theme to `edinburgh`:

i.e:

```
# Extensions
## Plugins: http://hexo.io/plugins/
## Themes: http://hexo.io/themes/
theme: edinburgh
```

### Theme configuration

#### Header menu
The menu is configured in your blog's `_config.yml`.
```
# Header
menu:
  About: /about
  Contact: /contact
  Instagram: https://www.instagram.com
  LinkedIn: https://www.linkedin.com
  Facebook: https://www.facebook.com
```

#### Favicon
The blog's favicon can be changed by replacing the theme's favicon image in `/themes/edinburgh/source/favicon/favicon.ico`.

#### Google Analytics tracking
The Google Analytics Tracking ID is configured in the theme's `_config.yml`.
```
# Google Analytics Tracking ID
google_analytics:
```

### Post configuration
For each post, specify additional information in the [front matter](https://hexo.io/docs/front-matter.html).

#### Post title
Use the title to specify the text displayed as the heading for your post.
```
title: My Awesome Portfolio Piece
```

#### Post image
Each post on this theme requires a cover image. If no cover image is provided, a default cover image is used. Specify your own image like this.
```
cover_image: /images/portfolio.jpg
```

### Creator
This theme was designed and created by [Sharvari Desai](http://www.sharvaridesai.com/).

## Bugs

If you have a question, feature request or a bug you need me to fix, please [click here](https://github.com/sharvaridesai/hexo-theme-edinburgh/issues/new) to file an issue.
