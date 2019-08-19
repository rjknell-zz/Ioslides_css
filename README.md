# Ioslides_css
CSS file for a modified Ioslides presentation for Rmarkdown

## Justification
The default CSS file for the Ioslides presentations that can be rendered from Rmarkdown is dense and not commented in any useful way. This CSS file will produce a modified set of slides with different formatting, and it is commented to allow for easy editing.

## How to use
You need to save the CSS file to a suitable directory (usually the one with your .Rmd file) and then link to it in your YAML headers, e.g.

```
---
title: "Test slides"
author: "Me"
date: "19/08/2019"
output:
  ioslides_presentation:
    css: slidestyles2.css
---
```

The slides will then be rendered using both the default CSS and slidestyles2, but entries in slidestyles2 will override the default options where necesssary.

To change the formatting you will need to edit slidestyles2.css, which will hopefully be made easier by the commenting.

## Test slides
There is a set of test slides available as an .Rmd file and also as the html.

## Final note

I am very much an amateur with .css files. If you see a mistake or a better way to do things please let me know.
