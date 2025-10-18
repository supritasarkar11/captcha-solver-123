# CAPTCHA Solver Web App

This is a simple, single-file responsive web application designed to demonstrate a CAPTCHA challenge and provide an interface for users to solve it. Built with vanilla JavaScript and styled using Tailwind CSS, it offers a clean and user-friendly experience.

## Features

*   **Responsive Design**: Adapts to various screen sizes, from mobile to desktop.
*   **Dynamic Image Loading**: Loads CAPTCHA images from a specified URL parameter or defaults to a local sample.
*   **User Input Interface**: Provides an input field for users to enter the CAPTCHA text.
*   **Basic Validation**: For the default `sample.png`, it validates against a pre-defined solution. For dynamic URLs, it simulates a submission process.

## How to Use

1.  **Save the file**: Save the provided `index.html` and `sample.png` in the same directory.
2.  **Open `index.html`**: Open the `index.html` file in your web browser.

### Loading Custom CAPTCHA Images

You can specify a custom image URL using the `url` query parameter in the browser's address bar.

**Example:**
`index.html?url=https://example.com/path/to/your/captcha.png`

When a custom URL is provided, the application will display the image but will not perform automated validation (as real-time OCR for arbitrary images is beyond the scope of a simple client-side HTML file). It will simply confirm the user's submission.

### Default CAPTCHA

If no `url` parameter is provided, the app will load `sample.png` as the CAPTCHA image. The expected solution for `sample.png` is `ADURB` (case-insensitive for validation purposes).

## Technologies Used

*   **HTML5**: Structure of the web page.
*   **Tailwind CSS (CDN)**: For rapid and responsive styling.
*   **Vanilla JavaScript**: For dynamic content loading and interaction logic.

## Project Structure

```
.
├── index.html
└── sample.png
```

## Disclaimer

This application is a demonstration for educational and illustrative purposes. A real-world CAPTCHA solver typically involves robust server-side image processing (OCR) and security considerations that are not implemented here.
