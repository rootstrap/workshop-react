# WORKSHOP JS ANIMA

This repository contains slides for the JS workshop for Anima.

The material is presented using [reveal.js](https://revealjs.com/), a HTML presentation framework.

You can visit [this site](https://rootstrap.github.io/workshop-js-anima) to access all the published content.

## Installation

1. Clone this repository.
1. Run `npm install`
1. Run `npm start`
1. That's it! Server should be running on `http://localhost:8000` by default.

## How to use

### Index page
When you start the server and go to the main page, you will see a list with all the classes. This screen is built in `index.html` file, so if you will add a new class, make sure to add a new link in this file just to keep an index.

### Access to classes
All the classes are located in `classes` folder. You can access to each one indicating the url in the browser (eg: `/classes/1.html`) or using the link in the index page.

### Add content to a class
We are using the reveal.js framework, so to be able to add a new slide, checkout the [documentation](https://revealjs.com/markup/). 

Each section tag is a new slide. You can use horizontal or vertical slides like this:
```html
<section>Horizontal Slide</section>
<section>
  <section>Vertical Slide 1</section>
  <section>Vertical Slide 2</section>
</section>
```

### How to add images
In the `examples` folder there are many examples that use images, markdown, different themes and other cool things. You can copy this code! 
