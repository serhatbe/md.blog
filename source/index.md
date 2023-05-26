-----------------------------------------------------------------------------
github     : https://github.com/casualwriter/casual-markdown-blog
title      : Blog with Markdown 
subtitle   : Simple
nav-group  : featured, new-3, tags, months
nav-width  : 320px
css-header : background:linear-gradient(to bottom right, #06c, #fc0); color:white
menu       : 
   Home    : ?
   github  : [home](https://serhatbe.github.io/md.blog/)
   Dark    : javascript:darkmode()
   About   : ?page=about.md
-----------------------------------------------------------------------------
<style comment="additional style">
#header { {{css-header}}  }
#left-panel  { width:{{nav-width}} }
#right-panel { left: calc({{nav-width}} + 20px) }
h1 { border-bottom:1px dotted grey }
.nav-post a  { color: teal }
.nav-tag  a  { color: #06c }
.nav-month a { color: grey }
.post-date   { font-size:12px; font-weight:400; }
.post-title  { font-size:16px; color:#333 }
.post-tags   { left-margin:20px; padding:4px; font-size:10px; color:green; font-weight:400 }
</style>

<div id="md-post">
# Featured 
## [Test](20230526-Test.md)
> date:2023/05/26, tags: `#markdown`
> 
> build blog site by markdown files in minutes.
> host on github, or other static web hosting  

## [Markdown as blog](20220820-markdown-as-blog.md)
> date:2022/08/20, tags: `#markdown`
> 
> build blog site by markdown files in minutes.
> host on github, or other static web hosting  

# Archives

### Sep 2022
   
### Aug 2022
                   
* 2022/08/20: [Markdown as blog](20220820-markdown-as-blog.md) { #markdown, #featured }
* 2022/08/10: [Is RegExp readable?](20220810-is-regexp-readable.md) { #regexp }

</div>
