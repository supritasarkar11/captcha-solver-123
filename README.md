# Captcha Solver UI

This project provides a simple, single-file HTML application for displaying and interacting with captcha images. It's designed to be a user interface where a human can view a captcha image and enter the corresponding text.

## Features

*   **Dynamic Image Loading**: Load captcha images from a URL specified in the query parameter (`?url=https://example.com/image.png`).
*   **Default Image**: Defaults to `sample.png` if no URL is provided.
*   **Responsive Design**: Built with Tailwind CSS for a modern, responsive user experience across various device sizes.
*   **User Input**: Provides an input field for users to enter the captcha text.
*   **Basic Validation**: Includes a simple client-side check for the provided `sample.png` to demonstrate functionality.

## Usage

1.  **Open `index.html` in your web browser.**
    *   By default, it will load `sample.png`.
    *   To load a different captcha image, append a `?url=` query parameter to the URL in your browser's address bar:
        `file:///path/to/index.html?url=https://example.com/your-captcha-image.png`
        (Note: Browser security might prevent direct loading of external HTTP images from a local `file://` URL without CORS enabled on the image server.)
2.  **Enter the text** you see in the captcha image into the input field.
3.  **Click "Submit Captcha"** or press `Enter`.

## Technologies Used

*   **HTML5**: Structure of the web page.
*   **Tailwind CSS**: For styling and responsive layout.
*   **JavaScript**: For dynamic content loading and user interaction.

## Contributing

Feel free to fork this repository, open issues, or submit pull requests.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
