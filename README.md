MI SITIO

**[HMFAYSAL V2](http://v2.theevilgenius.tk)** is a two column responsive Jekyll theme by Engineer [Hossain Mohd Faysal](http://hmfaysal.tk) featuring a slide out drawer menu in mobile browsers.

## HMFAYSAL V2 is all about:

* Responsive templates. Buscando aprender para ayudar.
* Estoy muyy felíz de estar aqui aprendiendo
* Minimal embellishments. Content first; other widget nonsense never.
* Large feature images for posts and pages.
* Simple and clear permalink structure.
* [Custom 404 page](http://v2.theevilgenius.tk/404.html) to get you started.
* Stylesheets for Pygments and Coderay [syntax highlighting](http://v2.theevilgenius.tk/articles/code-highlighting-post/) to make your code examples look snazzy.

![screenshot of HMFAYSAL V2 theme](http://v2.theevilgenius.tk/images/Jekyll-HMFAYSAL-Theme.jpg)

General notes and suggestions for customizing HMFAYSAL V2 Theme.

## Basic Setup

1. [Install Jekyll](http://jekyllrb.com) if you haven't already.
2. Fork the [Jekyll HMFAYSAL V2 Theme repo](http://github.com/hmfaysal/Jekyll-HMFAYSAL-V2-Theme/)
3. Clone the repo you just forked to your computer.
4. Edit `_config.yml` to personalize your site.
5. Check out the sample posts in `_posts` to see examples for pulling in large feature images, tags, and other YAML data.
6. Read the documentation below for further customization pointers and documentation.

[Demo the Theme](http://v2.theevilgenius.tk)

**Pro-tip:** Delete the `gh-pages` branch after cloning and start fresh by branching off `master`. There is a bunch of garbage in `gh-pages` used for the theme's demo site that I'm guessing you don't want on your site. Also type in `chcp 65001` if the prompt shows UTF-8 or IBM47 error.

---

## Setup for an Existing Jekyll site

1. Clone the following folders: `_includes`, `_layouts`, `assets`, and `images`.
2. Clone the following files and personalize content as need: `about.md`, `articles.html`, `index.md`, `feed.xml`, `sitemap.xml`
3. Set the following variables in your `config.yml` file:

``` yaml
title: Trabajos de Sully
description: Todo lo que se puede encontrar
disqus_shortname: sully-abdo
url: https://sullyonline.live

# Owner/sully abdo
owner: /Sully-abdo
name: Sully Gabriela Abdo Montejo
avatar: https://scontent.fmid3-1.fna.fbcdn.net/v/t39.30808-6/p526x296/269606322_1905393093181808_5314882369738981875_n.jpg?_nc_cat=108&ccb=1-5&_nc_sid=8bfeb9&_nc_eui2=AeFgSfvFZ5tRKJrr2yVzWr4Ku5p42bUoGrS7mnjZtSgatNCPqjygYC9fh8LaITcsXcOWV0HzaH_rqFXBzai40lgk&_nc_ohc=GsAxILUoRLYAX---SXd&_nc_ht=scontent.fmid3-1.fna&oh=00_AT9-26nr1VTtEsVOZSbfkhgHBHk9-dwdckPB1uJk4gopTA&oe=62023851
bio: "Soy lo que quiero ser"
email: 210300328@ucaribe.edu.mx
  # Social networking links used in footer. Update and remove as you like.
  twitter:        
#facebook: https://www.facebook.com/sully.abdo.1/     
github: sully-abdo         
  stackexchange:  
 #linkedin:       
  #instagram:      
  #flickr:         
  tumblr:         
  hmfaysalsocial:	
  # For Google Authorship https://plus.google.com/authorship
  google_plus:    

# Analytics and webmaster tools stuff goes here
google_analytics:   
google_verify:      
# https://ssl.bing.com/webmaster/configure/verify/ownership Option 2 content= goes here
bing_verify:         

# Links to include in top navigation
# For external links add external: true
links:
  - title: Menú
    url: /
  - title: Sobre
    url: /about/
  - title: Articulos
    url: /articles/
  - title: Setup
    url: /theme-setup/
  - title: Detalles
    url: /technical-details/
  - title: La estudiante de negocios
    url: http://www.theevilgenius.tk/
    external: true

# http://en.wikipedia.org/wiki/List_of_tz_database_time_zones
timezone:    America/New_York
future:      true
pygments:    true
markdown:    kramdown

```

---

## Preguntas?

Having a problem getting something to work or want to know why I setup something in a certain way? Ping me on Twitter [@hmfaysal](http://twitter.com/hmfaysal) or [file a GitHub Issue](https://github.com/hmfaysal/Jekyll-HMFAYSAL-V2-Theme/issues/new). And if you make something cool with this theme feel free to let me know.

---

## License

This theme is free and open source software, distributed under the [GNU General Public License](http://v2.theevilgenius.tk/LICENSE) version 2 or later. So feel free to use this Jekyll theme on your site without linking back to me or including a disclaimer. 
