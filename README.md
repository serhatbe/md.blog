## Casual-Markdown-Blog
Based on Casual-Markdown, [please see](https://casualwriter.github.io/casual-markdown/blog)


### Features

* single html
* no dependence in vanilla javascript
* support all browser
* dark mode or dark theme
* responsive, support mobile
* customized theme (by css style)

### Usage Guide

simply copy [index.html](https://github.com/casualwriter/casual-markdown-page/blob/main/source/index.html) to web server, or fork this repo. 

* config site at index.md (title, subtitle, header-color, navigation, etc..)
* start to write blog post using markdown
* to publish, just add the post in index.md by syntax 

~~~
* yyyy/mm/dd: [post-title](md-file) { #tags }
~~~

index.md is also shown as HOME page of blog site. 

below is sample setup from [Sample Blog: index.md](https://raw.githubusercontent.com/casualwriter/casual-markdown-blog/main/source/index.md)

~~~  
--------------------------------------------------------------------------
title      : Casual-Markdown's Blog 
subtitle   : Simple is the best
nav-group  : featured, new-3, tags, months
nav-width  : 320px
css-header : background:linear-gradient(to bottom right, #06c, #fc0); color:white
menu       : 
   Home    : ?
   Github  : https://github.com/casualwriter/casual-markdown-blog
   Dark    : javascript:darkmode()
   About   : ?page=about.md
--------------------------------------------------------------------------

<style comment="additional style">
......
</style>

<div id="md-post">

home page in markdown syntax...

## Archive

* yyyy/mm/dd: [Post Title](md file)  { #tag1, #tag2 }
* yyyy/mm/dd: [Post Title](md file)  { #tag1, #tag2 }
...
* yyyy/mm/dd: [Post Title](md file)  { #tag1, #tag2 }

</div>
~~~ 

### frontmatter for blog setup

* `title` := blog title
* `subtitle` := subtitle
* `nav-group` := featured // show blogs tagged by `featured`
* `nav-group` := new-n    // show new posts (n=number of new post)
* `nav-group` := tags     // show tags list
* `nav-group` := months   // show archive by month
* `nav-width` := 320px    // width of nav-panel
* `css-header` := background:green   // css style for header
* `theme` := dark        // show by dark theme (only dark theme available now)
* `menu` :=  ...         // top-menu 

### URL Parameters

* `index.html?post={md-post.md}`  show post of md-post.md 
* `index.html?tag={tag-name}`  list posts for specified tag
* `index.html?month=2022-08`  list posts for specified month
* `index.html?theme=dark`  show in dark theme
* `index.html?home=index-dark.md`  show blog site using index-dark.md as home/index
* `index.html?home=my-blog.md&theme=dark&pos=post01.md` show post01.md using my-blog.md in dark mode.

### Notes

* [alt-k] to toggle dark mode
* [alt-s] to view in html code (for developer)
* [ctrl-p] to print post
* in mobile mode (width<900), click on title to toggle nav panel

### History

* 2022/08/24: 0.60, first release
* to-do, more themes
 
