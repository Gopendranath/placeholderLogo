# Dynamic Image Viewer

This project dynamically generates and displays images with sequential numbers from `001` to `999`. The images are loaded from the Flaticon CDN.

## Features

- Displays all images from a specified URL range.
- Dynamically generates image URLs using JavaScript.
- Handles broken images gracefully by hiding them.

## Live Demo

[View the live demo here](https://your-live-link.com)

## How It Works

1. **Base URL:** The images are fetched from `https://cdn-icons-png.flaticon.com/512/2111/`.
2. **Dynamic Generation:** A loop generates all possible image URLs from `001` to `999`.
3. **Error Handling:** Any broken images (404 errors) are automatically hidden.

## Technologies Used

- HTML
- JavaScript
- CSS

## How to Use

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/dynamic-image-viewer.git
    ```
2. Open the `index.html` file in your browser to view the images.

## Contributing

Feel free to contribute to this project! Open an issue or submit a pull request with your ideas or improvements.

## License

This project is licensed under the MIT License.
