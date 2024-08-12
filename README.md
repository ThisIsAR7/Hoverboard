# Hoverboard

This project creates a dynamic hoverboard effect using HTML, CSS, and JavaScript. When the user hovers over squares in the grid, the squares change color and produce a glowing effect.

## Table of Contents
- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)


## Demo

To see a live demo of the hoverboard, open the `index.html` file in a web browser. You will see a grid of squares that change color and glow when you hover over them.

## Features

- **Dynamic color change**: Squares change to random colors on hover.
- **Glowing effect**: Each square produces a glowing effect when hovered.
- **Smooth transitions**: The color changes and glow effects are smoothly animated.

## Installation

To install and run the project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/ThisIsAR7/hoverboard.git
    ```
2. **Navigate to the project directory**:
    ```bash
    cd hoverboard
    ```
3. **Open `index.html` in your browser**:
    ```bash
    open index.html
    ```

## Usage

To use this project, simply open the `index.html` file in a web browser. The page will display a grid of squares that change color and glow when hovered over.

## Customization

- **Number of squares**: Change the `SQUARES` constant in `script.js` to increase or decrease the number of squares.
- **Colors**: Modify the `colors` array in `script.js` to change the available colors for the squares.
- **Square size**: Adjust the `height` and `width` properties in the `.square` class in `style.css` to change the size of the squares.
- **Grid size**: Adjust the `max-width` property in the `.container` class in `style.css` to change the overall size of the grid.

## Project Structure

The project consists of the following files:

1. **index.html**: The main HTML file that sets up the structure of the page.
2. **style.css**: The CSS file that styles the page.
3. **script.js**: The JavaScript file that contains the logic for the hoverboard effect.

### index.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>Hoverboard</title>
  </head>
  <body>
    <div class="container" id="container"></div>
    <script src="script.js"></script>
  </body>
</html>
