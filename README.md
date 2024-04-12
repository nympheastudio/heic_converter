# HEIC to JPG Converter

## Introduction
This project provides a simple web-based tool to convert HEIC images to JPG format using JavaScript.

## Features
- Convert HEIC files to JPG without the need for server-side processing.
- Simple and user-friendly interface.
- Efficient conversion with adjustable quality parameters.

## Prerequisites
- A modern web browser that supports ES6+ (e.g., Chrome, Firefox, Safari, Edge).

## How It Works
The script fetches an HEIC file based on the image name provided in the URL query string, converts it to a JPEG format using the `heic2any` library, and then displays the resulting JPG image in the browser.

## Usage
To use the converter, simply follow these steps:
1. Clone the repository to your local machine or download the source code.
2. Open the `index.html` file in your web browser.
3. Append the image parameter to the URL as a query string. For example:
https://yourdomain.com/index.html?image=your_image_file_name

## Error Handling
If the image cannot be loaded or the conversion fails, an error message will be displayed on the screen.

## Contributions
Contributions are welcome. Please fork the repository and submit a pull request with your enhancements.

## License
This project is licensed under the No License - you can use this code as you want

## Acknowledgements
- Thanks to the developers of the `heic2any` library for making HEIC to JPG conversion possible in JavaScript.


