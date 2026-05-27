# HTML Practice: Assignment 5

This folder contains the fifth assignment, exploring multi-page website creation by linking several HTML documents (cities) together using a shared CSS file.

## Technologies Used
*   **HTML**: To create the distinct pages (`cities.html`, `banglore.html`, etc.).
*   **CSS**: A centralized `styles.css` file to ensure a consistent look and feel across all the linked HTML pages.

## Core Concepts Covered
*   **Hyperlinks and Anchors (`<a>`)**: The fundamental mechanism of the World Wide Web. Using the `href` attribute to link from one HTML document to another, allowing users to navigate between the city pages.
*   **Relative Paths**: Understanding how to correctly link to files within the same directory structure (e.g., `href="banglore.html"`) instead of using absolute URLs.
*   **External Stylesheets**: Linking an external `.css` file using the `<link rel="stylesheet" href="styles.css">` tag in the `<head>` of multiple HTML documents. This demonstrates the principle of DRY (Don't Repeat Yourself) by sharing styling rules across the entire site.

## How to Run
Start by opening the main `cities.html` file in any modern web browser. You should be able to navigate to the other city pages clicking on the provided links.
