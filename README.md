# Modern Button
This repository contains a simple modern button implemented with HTML and CSS. The button has a pink background color and a smooth animation effect when hovered over.

## Getting Started
To get started, simply clone the repository and open the **index.html** file in your web browser.

**git clone <repository-url>**

**cd modern-button**

## Usage

The modern button is implemented as a div element with the class btn-pink. You can use this class to style any HTML element as the modern button.

**<div class="btn-pink">Hire Me</div>**

## Styles

The button is styled using the style.css file. Here's an overview of the styles applied:

**.btn-pink** : Styles the button with a pink background color, white text, padding, font size, and box shadow for a modern look.
**.btn-pink::before** : Creates a pseudo-element that covers the button and animates its background color from dark to light pink when hovered over.

## CSS Explanation
**::before Pseudo-element** : The ::before pseudo-element is used to create an overlay effect. It starts with a transform: scaleX(0); property, which means it's not visible. When the button is hovered over, the transform property is animated to scaleX(1);, making it visible with a smooth animation effect.

Feel free to use this modern button in your projects and customize it according to your needs! If you have any questions or suggestions, please feel free to open an issue or create a pull request. Happy coding!
