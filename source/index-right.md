-----------------------------------------------------------------------------
github     : https://github.com/casualwriter/casual-markdown-blog
title      : My Blog 
subtitle   : Simple is the best
nav-group  : featured, new-3, tags, months
nav-width  : 320px
menu       : 
   Home    : ?
   About   : ?page=about.md
-----------------------------------------------------------------------------
<style comment="show nav at right">
#header { xbackground: linear-gradient(to bottom right, #06c, #fc0); }
#left-panel  { right:0; left:auto; width: {{nav-width}} }
#right-panel { left:0; border-right:1px solid grey; right:calc({{nav-width}} + 20px) }
h1 { border-bottom:1px dotted grey }
.nav-post a  { color: teal }
.nav-tag  a  { color: #06c }
.nav-month a { color: grey }
.post-date   { font-size:10px; font-weight:400; color:#aaa }
.post-title  { font-size:16px; }
.post-tags   { left-margin:20px; padding:4px; font-size:10px; color:green; font-weight:400 }
</style>

<div id="md-post">
# Featured

## [Markdown as blog](20220820-markdown-as-blog.md)
> build blog site by markdown files in minutes.
> host on github, or other static web hosting  

## [Is RegExp readable?](20220810-is-regexp-readable.md)
> ![does regexp make the code not readable?](campo03.jpg)
> date: 2022/08/10, tags: `#regexp, #web-dev`
> 
> Sure not. But does regexp make the code not readable?


# Archives

</div>
