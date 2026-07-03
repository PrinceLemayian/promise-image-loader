# Promise Image Loader

A JavaScript project that explores modern asynchronous programming by loading images with **Promises**, **async/await**, and **Promise.all()**. It demonstrates both sequential and parallel image loading while handling asynchronous operations cleanly and efficiently.

## Features

- Create custom Promises for asynchronous image loading
- Load images sequentially using `async/await`
- Pause execution between image transitions
- Load multiple images concurrently with `Promise.all()`
- Apply CSS classes to images after all have loaded
- Gracefully handle image loading errors

## Technologies

- HTML5
- CSS3
- JavaScript (ES6+)

### JavaScript Concepts Practiced

- Promises
- Creating custom Promises
- Promise chaining
- `async` / `await`
- `Promise.all()`
- Error handling with `try...catch`
- DOM Manipulation
- Event Listeners

## Project Structure

```text
.
├── img/
│   ├── img-1.jpg
│   ├── img-2.jpg
│   └── img-3.jpg
├── index.html
├── style.css
└── script.js
```

## How It Works

### Sequential Loading (`loadNPause`)

1. Load the first image.
2. Wait until it has finished loading.
3. Display it for two seconds.
4. Hide the image.
5. Repeat the process for the next image.

This demonstrates how `async/await` can make asynchronous code read like synchronous code.

### Parallel Loading (`loadAll`)

1. Create an array of image-loading promises.
2. Wait for every image to load using `Promise.all()`.
3. Once all images have loaded successfully, apply the `parallel` CSS class to each image.

This demonstrates how multiple asynchronous tasks can run concurrently instead of one after another.

## Running the Project

1. Clone the repository:

```bash
git clone https://github.com/PrinceLemayian/promise-image-loader.git
```

1. Navigate to the project directory.

2. Open `index.html` in your browser, or use a local development server such as **VS Code Live Server**.

## Learning Objectives

This project was built to practice:

- Creating custom Promises
- Resolving and rejecting Promises
- Promise chaining with `.then()`
- Converting Promise chains to `async/await`
- Waiting for multiple asynchronous operations with `Promise.all()`
- Error handling with `try...catch`
- Working with asynchronous DOM operations
- Structuring clean, readable asynchronous JavaScript

## Future Improvements

- Lazy-load images as they enter the viewport
- Display loading indicators while images download
- Support dynamic image galleries
- Retry failed image requests
- Add image fade-in/fade-out animations

## License

This project is for educational purposes.
