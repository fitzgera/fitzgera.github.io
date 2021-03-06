---
title: "Post: Technical Info About This Site"
permalink: /TechnicalInfo/
excerpt_separator: "<!--more-->"
categories:
  - Post About this site
tags:
  - Post About this site
  
toc: true
toc_label: "On this page"
toc_icon: "cog"  
---

## Main Points
* This site is a GitHub Pages resource hosted on [github.com](https://github.com/)
* [Source Code](https://github.com/fitzgera/fitzgera.github.io) on github.com

## Theme and Links
* The site uses the [Minimal Mistakes theme](https://github.com/mmistakes/minimal-mistakes)
* [Minimal Mistakes documentation](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)
* [Source Code](https://github.com/mmistakes/minimal-mistakes/tree/master/docs) for Minimal Mistakes documentation. Useful to be able to look here and see how things are done.


* Minimal Mistakes example [Site Starter](https://mmistakes.github.io/mm-github-pages-starter/)
* Minimal Mistakes example [Site Starter Source Code](https://github.com/mmistakes/mm-github-pages-starter)

* Krish Shen's [site](https://krisshen.me/) and how to make the [Header Sticky](https://krisshen.me/project_website/how-to-make-header-sticky/)

* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)


## Main Steps
* Create an initial [GitHub Pages Web Site](https://help.github.com/en/github/working-with-github-pages/creating-a-github-pages-site)
* Clone the example Site Starter site on GitHub using the links above and copy/overwrite the files in the  initial site you just created in the previous step
* Update [_config.yml](https://github.com/fitzgera/fitzgera.github.io/blob/master/_config.yml) with the main site settings that you want
* Update [navigation.yml](https://github.com/fitzgera/fitzgera.github.io/blob/master/_data/navigation.yml) for top menu contents 
* Update [main.scss](https://github.com/fitzgera/fitzgera.github.io/blob/master/assets/css/main.scss) to:
  * Make masthead/header "sticky" (it doesn't move when you scroll up and down)
  * Change  background colour of masthead/header to  #ac4142;
  * change colour of masthead/header menu  items to white
* Create [category-archive.md](https://github.com/fitzgera/fitzgera.github.io/blob/master/_pages/category-archive.md) and [tag_archive.md](https://github.com/fitzgera/fitzgera.github.io/blob/master/_pages/tag-archive.md) files. I put these in the [_pages](https://github.com/fitzgera/fitzgera.github.io/tree/master/_pages) folder. But I don't know if they need to be here. See [Issue 1764](https://github.com/mmistakes/minimal-mistakes/issues/1764)



## To Do....
1. Figure out how to change the footer, especially the social media links and put in a privacy policy link
2. The home/splash page is incorrectly created
3. Maybe embed a Twitter feed on the home page
4. The "hamburger" menu text (on small screens) is the wrong colour
5. Can tags and Categories be used on normal pages.

## Status 
This is a work in progress and I am still learning about the various technologies 

## Bits and Pieces

Some technical information about this site
<!--more-->

This post has a manual excerpt `<!--more-->` set after the second paragraph. The following YAML Front Matter has also be applied:

```yaml
excerpt_separator: "<!--more-->"
```

some more details go here
