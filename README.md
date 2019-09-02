# Hexo theme: Apollo

**This hexo theme is modified from SANOGRAPHIX.NET**

Original (Tumblr theme): https://github.com/sanographix/tumblr/tree/master/apollo

Demo: https://blog.zhanghai.me/

## Integration

### Install

``` bash
$ git submodule add git@github.com:zhanghai/hexo-theme-apollo.git themes/apollo
```

**Apollo requires Hexo 2.4 and above.**

### Update

``` bash
cd themes/apollo
git pull
```

## Configuration

``` yml
# Header
menu:
    Home: /
    Archives: /archives
rss: /atom.xml

# Content
more_link: true
fancybox: true

# Miscellaneous
google_analytics:
favicon: /favicon.png
```

- **menu** - Navigation menu
- **rss** - RSS link
- **more_link** - "Read More" link at the bottom of excerpted articles. `false` to hide the link.
- **fancybox** - Enable [Fancybox](http://fancyapps.com/fancybox/)
- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path
