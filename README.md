# Captcha Solver Demo

This project provides a simple, client-side demonstration of a Captcha interaction. It features a responsive HTML page built with Tailwind CSS, designed to display a captcha image and allow users to input their solution. While it doesn't include a real server-side captcha solving mechanism, it allows for loading custom captcha images via URL parameters and offers a basic verification for a default image.

## Features

*   **Responsive Design:** Optimized for various screen sizes using Tailwind CSS.
*   **Dynamic Image Loading:** Load captcha images using a `?url=` query parameter (e.g., `index.html?url=https://example.com/captcha.png`).
*   **Default Captcha:** Displays a `sample.png` image by default.
*   **Client-Side Verification:** Provides immediate feedback for the default captcha image ("ADUR3"). For custom images, it acknowledges the input but cannot perform server-side verification.
*   **Modern UI:** Clean and interactive interface.

## How to Use

### Running Locally

1.  Save the `index.html`, `README.md`, `LICENSE`, and `sample.png` files into the same directory.
2.  Open `index.html` in your web browser.

### Loading a Custom Captcha Image

You can specify a captcha image URL directly in your browser's address bar or using the input field on the page:

*   **Default (using `sample.png`):**
    `file:///path/to/your/project/index.html`
*   **With a custom image:**
    `file:///path/to/your/project/index.html?url=https://example.com/your-captcha-image.png`
    (Replace `https://example.com/your-captcha-image.png` with the actual URL of your captcha image.)

### Solving the Captcha

1.  Observe the characters displayed in the captcha image.
2.  Type the characters into the input field.
3.  Click the "Submit" button.

For the default `sample.png` image, the correct solution is **ADUR3**.

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **Tailwind CSS:** For styling and responsive design.
*   **JavaScript:** For dynamic behavior, image loading, and client-side interaction.

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more details.