# International Relations Wing, IIT Kanpur

This is the README file for the website of the International Relations Wing, IIT Kanpur.

## Table of Contents
1. [Introduction](#introduction)
2. [How to Use](#how-to-use)
   - [Editing the Website](#editing-the-website)
   - [Adding Photos](#adding-photos)

## Introduction
This website serves as a platform for the International Relations Wing at IIT Kanpur to showcase various information including scholarships, disciplines offered, events, and more. It's built using HTML and CSS.

## How to Use

### Editing the Website
To edit the website, you can simply modify the HTML and CSS files. Here's how you can edit different parts:

#### Header and Navigation
- The header and navigation section is defined in `index.html` within `<header>` and `<nav>` tags.
- You can change the logo by replacing `iitk-logo.png` with your desired logo. Make sure to keep the same file name and format.
- Edit the navigation links by modifying the `<li>` elements under `<nav>`.

#### Sections
- Each section (e.g., Gallery, About Institute, Disciplines Offered, etc.) is defined in `index.html` within `<section>` tags.
- You can edit the content within each section by modifying the text and images accordingly.

#### Application Form
- The application form is located within the `<section id="applicationform">` in `index.html`.
- You can add or remove form fields by modifying the HTML form structure.
- To change the action of the form, edit the `action` attribute of the `<form>` tag.
- Adjust form styles in `style.css`.

### Adding Photos
To add photos to the Gallery section:
1. Make sure your photos are in the same directory as your HTML file.
2. Add an `<img>` tag within the `<section id="gallery">` in `index.html`.
   - Replace photo1.jpeg with the filename of your photo and provide a suitable description in the alt attribute.
   ```html
   <img src="photo1.jpeg" alt="Description of the photo">
