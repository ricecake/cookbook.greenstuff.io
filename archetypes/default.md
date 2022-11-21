---
draft: false
date: {{ .Date }}

title: "Title for your recipe"
tagline: "A short tagline for your recipe"
tags: [] #tags for your recipe

author: {{ .Site.Params.front.defaultAuthor | default "Us" }}

servings: 4
calories: 300 #in kcal #can be BLANK

cook: true # If we are cooking this, leave true, if we are cooling set to false
prep_time: 15 #in minutes #can be BLANK
cook_time: 8 #in minutes or hours #can be BLANK
cook_increment: minutes # set to minutes or hours

recipe_image: {{ .Site.Params.front.defaultImage | default "images/defaultImage.png" }} #The image for your recipe
image_width: {{ .Site.Params.front.defaultImageWidth | default 512 }}
image_height: {{ .Site.Params.front.defaultImageHeight | default 512 }}

# For ingredient subheadings (if you use them), please use the h4 header.  For print view I have those elements targeted
---


## Ingredients

#### Ingredient Subheading

- First Ingredient
- Second Ingredient [^1]

## Directions

1. Step One
   1. Sub Step One
2. Step Two

#### Footnotes

[^1]: Footnote 1
