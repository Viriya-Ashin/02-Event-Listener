# Click Counter HTML Template

This HTML template creates a simple click counter web page with increment and decrement functionality. It includes references to external CSS for styling and JavaScript for interactivity.

## Key Elements

- **DOCTYPE Declaration**: Defines the document type and HTML version.
- **HTML Language Attribute (`<html lang="en">`)**: Sets the language of the document to English.
- **Character Encoding (`<meta charset="UTF-8">`)**: Ensures the document is displayed with the correct character set.
- **Viewport Configuration (`<meta name="viewport" content="width=device-width, initial-scale=1.0">`)**: Makes the website responsive by setting the viewport width to the device width.
- **IE Compatibility (`<meta http-equiv="X-UA-Compatible" content="ie=edge">`)**: Ensures the document is rendered using the latest Internet Explorer rendering engine.
- **Title (`<title>Click Counter</title>`)**: Sets the title of the document, which appears in the browser tab.
- **External CSS Link (`<link rel="stylesheet" href="./assets/css/style.css">`)**: Links to an external CSS file for styling the webpage.
- **Wrapper Container (`<div class="wrapper">`)**: A wrapper div to contain the main content of the page.
- **Content Container (`<div class="container">`)**: A container div for organizing content.
- **Card Contents (`<div class="card-contents">`)**: A div to hold the interactive elements.
- **Count Display (`<h4>Current Count: <span id="count">0</span></h4>`)**: Displays the current count value, starting at 0.
- **Decrement Button (`<button id="decrement">Decrement</button>`)**: A button to decrement the count.
- **Increment Button (`<button id="increment">Increment</button>`)**: A button to increment the count.
- **External JavaScript Link (`<script src="./assets/js/script.js"></script>`)**: Links to an external JavaScript file for adding interactivity to the webpage.

## Usage

1. **Structure**: The HTML structure includes a wrapper, container, and card contents to organize the elements neatly.
2. **Styling**: External CSS is linked to provide consistent styling for the webpage.
3. **Interactivity**: External JavaScript is linked to handle the increment and decrement functionalities.

# JavaScript Code for Click Counter Functionality

This script manages a click counter by incrementing or decrementing a displayed count based on button clicks. The code updates the DOM to reflect the current count value.

## Key Components

- **Counter Variable (`count`)**: Initializes the counter value to 0.
- **Element Selection**: Uses `document.querySelector` to select the increment and decrement buttons and the count display element.
- **Update Function (`setCounterText`)**: Updates the displayed count value on the webpage.

## Event Listeners

- **Increment Button**: Increases the count by 1 and updates the display when the increment button is clicked.
- **Decrement Button**: Decreases the count by 1 (if the count is greater than 0) and updates the display when the decrement button is clicked.



* A click is just one type of DOM event. What are some others?
Some other types of DOM events include:

- **Mouse Events**: `mouseover`, `mouseout`, `mousedown`, `mouseup`, `mousemove`, `dblclick`
- **Keyboard Events**: `keydown`, `keypress`, `keyup`
- **Form Events**: `submit`, `reset`, `focus`, `blur`, `change`, `input`
- **Window Events**: `load`, `unload`, `resize`, `scroll`
- **Touch Events**: `touchstart`, `touchmove`, `touchend`, `touchcancel`

