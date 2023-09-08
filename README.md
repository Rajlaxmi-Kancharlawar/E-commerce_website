# Store Website Documentation

## Overview

This documentation provides an overview of the structure and functionality of the "Store" website, which is built using HTML and CSS.



## 1. Introduction

The "Store" website is designed to showcase and sell various clothing items. It features a clean and modern design with a navigation menu, promotional content, and a product display section. The website includes the use of icons from Font Awesome and utilizes HTML, CSS, and JavaScript to create a responsive and interactive user experience.

## 2. HTML Structure

## 2.1. Document Type Declaration

```html
<!DOCTYPE html>
```

This line specifies that the document is an HTML5 document.

## 2.2. HTML Structure

- The HTML structure is enclosed in the `<html>` element and specifies the document's language as English (`en`).

- The `<head>` section contains meta information, the page title, external stylesheet links, and an external Font Awesome icon library link.

- The `<body>` section contains the main content of the webpage.

## 2.3. Navigation Bar

- The navigation bar (`<nav>`) contains a logo, which is an icon and the "Store" title.

- It also includes an unordered list (`<ul>`) with list items (`<li>`) for navigation links, including "Home," "About Us," "Shop," "Contact," and a shopping cart icon.

## 2.4. Main Content

- The main content is enclosed in a `<div class="content">` container.

- It consists of a promotional text section with a heading, subheading, description, and a "Buy Now" button.

- The product display area contains a large image (`<img>`) and a row of small product images (`<div class="small-img">`) that users can click to change the large image.

## 3. CSS Styling

- The website's styling is controlled by an external CSS file named "style.css."

- CSS rules define the layout, colors, fonts, and responsiveness of various elements on the webpage, including the navigation bar and content sections.

## 4. JavaScript Functionality

- JavaScript code is included in the HTML to enable dynamic image swapping.

- The `myTshirt` function is defined, which takes a parameter representing an image source and updates the large image source (`bigImage.src`) when a small product image is clicked.

---
This documentation provides an overview of the structure and functionality of the "Store" website. 
