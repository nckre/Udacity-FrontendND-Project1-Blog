# Personal Blog Website
## Udacity Frontend Nanodegree - Project 1
_______________________

## Introduction
### What is this project about?
This project is a sample travel blog website built with HTML and CSS. Popular CSS layout modules like Flexbox, Grid and Media queries are used to create a structured, mobile-responsive website layout.


### How is this document structured?
This ```README.md``` describes the HTML markup language and CSS style sheet language used in the project.
1. HTML
2. CSS
_______________________

## HTML
The travel blog consists of two HTML pages: 
1. Blog Index 
2. Berlin Blog Page
The blog [Index](index.html) is an overview of different cities, which each stand for a blog post entry. Only one of these cities, [Berlin](berlin.html), has been populated with content.
_______________________

## CSS
### Grid
The blog uses a total of three CSS files:
* [Style](css/style.css) defines the overall layout of both types of HTML pages
* [Blog-Grid](css/blog-grid.css) defines the layout of the main area of the index page
* [Blog-Post](css/blog-post.css) defines the layout of the main area of the blog post page
Both types of pages are structured using a grid layout. Both the index and blog post page consist of 4 grid elements:
1. Header
2. Main
3. Social Sidebar (hidden for mobile layout)
4. Footer
The main area changes depending on the type of page:
* Index: Main area is a nested grid of picture elements. Hovering over a picture element reveals the link to the respective blog post.
* Blog page: Main area is a sequence of entries. Each entry is a nested grid with a headline, a box for picture and a box for written content.
### Flexbox
* Header & Footer: Containers for flex elements. 
* Sidebar: The sidebar is an empty area with a fixed sidebar as an overlay. This fixed sidebar is a flex container for the different social media links. 
* Main: Grid cells are flex containers for items like pictures
### Media queries
The page has a total of 4 media breakpoints:
* Up to 768px: Index grid has a single column
* Between 768px to 1280px: Index grid has two columns
* Between 1280px to 1600px: Sidebar appears; index grid has 3 columns
* Ove 1600px: Sidebar remains; index grid has 4 columns 
