# GDL Sass Tools
GDL(Global Design Language) Sass Tools is an abstract and reusable Sass tools library. It includes mixins, maps, functions and utility classes.

## Installation
`npm -i gdl-sass-tools`

## How to use
Import library in whatever CSS file you need it.

`@import 'node_modules/gdl-sass-tools/tools'` 
`@import 'node_modules/gdl-sass-tools/utilities'`

Otherwise you simply import the compiled file, utility.css or utility.min.css into your head and in your ITCSS system, import the tool.scss file.

## Requirements
It's mandatory to set the variable **$gutter** in your projects Settings file (e.g. `settings/_settings.scss`).
