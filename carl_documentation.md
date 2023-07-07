# Webpage Creation Documentation

## Introduction

This documentation provides a detailed overview of the process involved in creating a webpage using HTML, CSS, and JavaScript. It covers the languages used, the implementation of different components, and the deployment of the project.

## Languages Used

The webpage was created using the following languages:

### HTML

HTML (HyperText Markup Language) was used to create the main structure of the webpage. It defines the content, including images, text, and other elements.

### CSS

CSS (Cascading Style Sheets) was used to give the webpage the desired look and feel. It was used to define the colors based on the style guide and apply them to the webpage. CSS was also responsible for animating the fade-in and fade-out effects of text during scrolling.

### JavaScript

JavaScript was primarily used for implementing the scrolling effect and the rotating logo. The scrolling effect involved detecting the position of the viewport on the page and changing the opacity of text accordingly. The rotating logo was achieved using ThreeJS, a JavaScript framework for working with 3D objects rendered inside the browser using WebGL.

### ThreeJS

ThreeJS was utilized to create the rotating logo. It is a JavaScript framework for working with 3D objects and rendering them in the browser using WebGL. By creating a scene and a camera, the framework allows for the addition of 3D objects and lighting to create the desired visual scene. In this case, the 3D logo in OBJ format was loaded using an OBJLoader and assigned a black mesh material.

## Process

### Mockup

The initial step involved creating a mockup of the homepage using AdobeXD, a design tool similar to Figma. The mockup served as a reference for the webpage's layout and design. Although it was possible to export the mockup directly into HTML and CSS, this approach resulted in bloated code with approximately 8000 lines. Hence, it was decided to code the webpage manually, referring to the mockup.

### 3D Logo

The logo designed by Luca was taken and imported into Photoshop. The 3D extrude feature in Photoshop was used to create a 3D object with a depth of 50 pixels. The file was then exported in OBJ format to be imported and utilized with ThreeJS for the rotating logo effect.

### Coding

The coding process involved the following steps:

1. Creation of Main Containers: Five main containers were created based on the style guide, each assigned a background color specified in the guide.

2. Placement of Images and Text: Images and text content were placed within the containers, following the layout and design outlined in the mockup.

3. CSS Styling: The webpage was styled using flexboxes, desired fonts, and other CSS properties. The goal was to achieve the desired visual presentation and layout as per the mockup.

4. ThreeJS Integration: A ThreeJS scene was created inside a flexbox container located at the top of the page, next to the logo. This allowed for the rendering and manipulation of the 3D rotating logo.


## Deployment

The project was deployed as a static webpage using Render, a hosting platform. Render facilitates the deployment of static pages directly from a GitHub or GitLab repository. It provides an easy and streamlined process for deploying not only static pages but also web services like Node.js and Ruby on Rails projects.

By utilizing Render, the webpage was made accessible to users, allowing them to view and interact with the content through a web browser.