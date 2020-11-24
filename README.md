# Spider PC - Building Customizing And Upgrading Computers

Code Instytute - Milestone Project 1

This project is a four-page webside to bulding customizing and upgrading computers. The purpose of the website is to create personalized computers by enthusiasts who put emphasis on user projects to make their computers unique and fully personalized to their needs.
1. Font familly Used
+ Roboto:ital - to style inside button text and navigation bar menu, hedings H1;
+ Handlee - to style feedbacks.
+ Roboto+Mono:ital - to style feedback footer.
+ Lato:ital - to style all of the other content of the webpage.


+ Webside Showcase

# UX

## As a owner of the webpage:

+ I want to make users aware of the benefits they can achieve by building their own computer.
+ I want to build unique PCs.
+ I want to research various solutions / types of components to meet the customers needs.
+ I want to create a clear, concise and easy to navigate website.

## As a customer

+ I want to research the best price for components.
+ I want to get best warranty option for the product.
+ I want my computer to be built by profesionals who will understend all my needs.
+ I want an easy to navigate website.

## My project proposal can be download 
[here.](https://c86735f1-c044-4081-b870-fcb94f6ff86b.ws-eu01.gitpod.io/files/download/?id=36988fa9-edcb-4057-907c-d1fdc3ab5572)
<a href="https://c86735f1-c044-4081-b870-fcb94f6ff86b.ws-eu01.gitpod.io/files/download/?id=b6abc7b9-add2-4a51-925a-c385c441f6f6" download>Click to Download</a>

+ Home
<img src="readme/wireframe/Home.png">

+ About
<img src="readme/wireframe/About.png">

+ Offers
<img src="readme/wireframe/Offers.png">

+ Contact
<img src="readme/wireframe/Contact.png">


# Features

## Existing Features

## Features Left to Implement

# Technology Used

## In this project I use the following technologies.

1. [HTML](https://en.wikipedia.org/wiki/HTML) - to creating structure and layout of the webpsite
1. [CSS](https://en.wikipedia.org/wiki/CSS) - to styling the website.
1. [Bootstrap](https://getbootstrap.com/) - for design and customize responsive mobile-first sites.
1. [Fontawesome](https://fontawesome.com/start) - for icon style.
1. [Google font](https://fonts.google.com/) - for font style.
1. [Balsamiq](https://balsamiq.com/wireframes/) - to create wireframes.
1. [GIMP](https://www.gimp.org/) - for rendering backgroung images

# Testing

## [W3C Markup Validation Service](https://validator.w3.org/)  
+ to validate code

### Error

1. Index.HTMLhtml
+ Img element missing alt atribute in feedback section.
+ Attribute novalidate not allowed on element div in modal class.
+ Image in to big resolution
+ Attribute wfd-id not allowed on element button.(line 51, column 25; to line 51, column 132)
+ Attribute href not allowed on element button. 
+ Element style not allowed as child of element body 

1. About.html
+ Attribute wfd-id not allowed on element button.(line 51, column 25; to line 51, column 132)

1. Offers.html
+ width and heigh insert inline whith img for free item.

### Error Fix

1. Index.html
+ Add alt artibut in to the feedback img.
+ Remove novalidate atribute from div at modal class.
+ Replaced img whith lower resolution to improve loading the webpage.
+ Remove wfd-id artibut from button element.
+ Change button to a class to remove error whith href.

1. About.html
+ Remove wfd-id artibut from button element

1. Offers.html
+ Remove inline size from img and ann in to style.css

### Error to be fixed in the future

1. Element style not allowed as child of element body in index.html.(line 22, column 5; to line 22, column 11)

## [Lighthouse 6.4.0] 
to testing 
1. Performance - to check how fast web page is loaded
2. Accessibillity - for contrast, navigation, names and labels
3. Best practice - for user experiance
4. SEO - for mobile friendly

# Bugs and Problems

1. Missing comments when commiting changes
+ Create css file - opaque-overlay, jumbotron, collout-container 
+ Fix img display for wireframe in README.md

1. The button responsible for collaps the text remains active even if it should be turned off in acordion container - about.html.
+ Fix - remove blocking collapse attribute for devices above small and add pointer to each collaps section.

1. Offers table override navigation bar on the extra small screen - offers.html
+ Fix - turn off visibility on the small screen and below.

1. Column not display properly on screen above 1024pix.
+ Fix - add column display ruls for screen above large.

1. Scrolling bar displayed in offers card.
+ Fix - blocking display in all web browser platform.
1. Improve UX after 

# Deployment

# Credits

1. [Benchmark.pl](https://www.benchmark.pl/) - Thanks to the Editors of Benchmark.pl for consent to the use of photos from articles in accordance with the copyright by providing the source. 