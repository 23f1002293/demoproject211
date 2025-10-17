# Renewable Energy Essay Generator

## Summary

This is a minimal, single-page, interactive web application that generates a short essay on the importance of renewable energy sources. The user is presented with a pre-filled topic and can click a button to display the essay on the page. The application is built with vanilla HTML, CSS, and JavaScript, with no external dependencies.

## Setup

No installation or build process is required. Simply open the `index.html` file in any modern web browser.

1.  Clone or download the repository/files.
2.  Navigate to the directory containing the files.
3.  Double-click `index.html` or open it using your browser's "File > Open" menu.

## Usage

1.  Open `index.html` in your browser.
2.  The input field will be pre-filled with the essay topic: "Write a short essay on the importance of renewable energy sources."
3.  Click the "Generate Essay" button.
4.  The generated essay will appear below the button.

## Code Explanation

-   **`index.html`**: This single file contains all the necessary code.
    -   **HTML**: The structure of the page, including a title, a form with a text input and a submit button, and a `div` element (`#essayOutput`) to hold the generated content.
    -   **CSS**: Basic styling is included within a `<style>` tag in the `<head>` for a clean and centered layout. It styles the main container, form elements, and the output area.
    -   **JavaScript**: The logic is contained within a `<script>` tag at the end of the `<body>`.
        -   It adds a `submit` event listener to the form.
        -   When the form is submitted, `event.preventDefault()` is called to stop the page from reloading.
        -   A pre-written essay is stored in a template literal.
        -   The `innerHTML` of the `#essayOutput` div is updated with the essay content, which is formatted with `<p>` tags for proper paragraph structure.

## Version Update Information

-   **v1.0.0** (2023-10-27)
    -   Initial release.
    -   Includes HTML structure, CSS styling, and JavaScript for essay generation.

## License

This project is licensed under the MIT License.
