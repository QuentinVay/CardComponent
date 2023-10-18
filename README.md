# CSS Card Component

This project showcases an example of a card component created using CSS for layout purposes, including an image, a title, text, information, and a notification. Below, you'll find details of the implementation and why this solution was chosen.

## Table of Contents

- [Preview](#preview)
- [Project Structure](#project-structure)
- [CSS Layout](#css-layout)
- [Choice of Solution](#choice-of-solution)
- [How to Use](#how-to-use)

## Preview

![Card Preview](/screenshot.png)

## Project Structure

The project structure is straightforward and consists of the following elements:

- `index.html`: The HTML page where the card component is embedded.
- `styles.css`: The CSS file that contains styles for the card component layout.
- `src/assets/underthegrave.jpg`: The image used in the card.

## CSS Layout

The card component uses CSS styles to lay out different elements. Here's an overview of the CSS structure:

- The global card component is styled with a drop shadow, rounded border, and a fixed width.
- The image part occupies 33% of the width of the card component, while the text part occupies 67%.
- The `.titleCard` and `.textCard` elements inside the text part are vertically aligned below each other using `display: flex` and `flex-direction: column`.
- The `.infCard` and `.noticeCard` elements have specific styles for alignment and presentation.

## Choice of Solution

I chose to use CSS layout to create the card component because it offers great flexibility in terms of customization and control over the layout of elements. CSS layout allows for creating responsive layouts and is widely supported by web browsers.

I also used the SCSS preprocessor to organize the code more efficiently and make maintenance easier. The use of reusable classes like `.imageCard`, `.titleCard`, `.textCard`, `.infCard`, and `.noticeCard` allows for efficient management of each component of the card.

## How to Use

1. Clone this repository to your local machine.
2. Open the `index.html` file in a web browser to see the card component in action.
3. Explore the `styles.css` file to understand how the styles are applied.
4. Customize the styles and content to meet your specific needs.

Feel free to explore, modify, and customize this card component for your projects. If you have any questions or suggestions, please don't hesitate to share them!

