# Promise Image Loader

A simple JavaScript project demonstrating how to use **Promises** to load images asynchronously, display them sequentially, and delay transitions between images.

## Features

- Load images asynchronously using Promises
- Wait for an image to fully load before displaying it
- Display images one at a time
- Hide the current image after a delay
- Gracefully handle loading errors

## Technologies

- HTML5
- CSS3
- JavaScript (ES6+)
  - Promises
  - DOM Manipulation
  - Event Listeners

## Project Structure

```text
.
├── img/
│   ├── img-1.jpg
│   └── img-2.jpg
├── index.html
├── style.css
└── script.js
```

## How It Works

1. A new image element is created.
2. The image source is assigned.
3. The Promise resolves once the image has successfully loaded.
4. The image is added to the page.
5. After a 2-second delay, the image is hidden.
6. The next image is loaded and the process repeats.

## Running the Project

1. Clone the repository:

```bash
git clone https://github.com/PrinceLemayian/promise-image-loader.git
```

1. Open the project folder.

2. Launch `index.html` in your browser (or use a local development server such as VS Code Live Server).

## Learning Objectives

This project was built to practice:

- Creating custom Promises
- Resolving and rejecting Promises
- Chaining asynchronous operations with `.then()`
- Error handling with `.catch()`
- Coordinating asynchronous tasks in JavaScript

## License

This project is for educational purposes.
