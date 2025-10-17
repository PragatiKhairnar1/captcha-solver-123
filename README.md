# CAPTCHA Solver Web Application

This is a simple, single-file responsive web application designed to present and verify a CAPTCHA solution. It's built using plain HTML, JavaScript, and styled with Tailwind CSS.

## Features

-   **Responsive Design**: Utilizes Tailwind CSS for a clean, mobile-first, and responsive user interface.
-   **Dynamic Image Loading**: Displays a CAPTCHA image, defaulting to `sample.png` but capable of loading images from a URL provided as a query parameter.
-   **User Input & Validation**: Allows users to enter the CAPTCHA text and validates their input against a predefined solution.
-   **Clear Feedback**: Provides immediate feedback to the user on whether their CAPTCHA attempt was successful or not.

## How to Run

1.  **Save Files**: Ensure `index.html`, `README.md`, `LICENSE`, and `sample.png` are all saved in the same directory.
2.  **Open in Browser**: Open the `index.html` file directly in your preferred web browser.

## Usage

### Default CAPTCHA Image

To use the default `sample.png` image (as provided):

Open `index.html` in your browser:
```
file:///path/to/your/folder/index.html
```

### Custom CAPTCHA Image from URL

You can specify an image URL using the `url` query parameter. For example:

```
file:///path/to/your/folder/index.html?url=https://example.com/some-other-captcha.png
```

Replace `https://example.com/some-other-captcha.png` with the actual URL of your desired CAPTCHA image.

### Solving the CAPTCHA

The provided sample image (`sample.png`) displays the text "ADURS". Enter this text into the input field and click "Submit" to see a success message.

## Technologies Used

-   **HTML5**: Structure of the web page.
-   **Tailwind CSS**: Utility-first CSS framework for styling.
-   **JavaScript**: For dynamic image loading and client-side validation logic.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.