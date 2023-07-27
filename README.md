# Dynamic Croppie - Crop Images Dynamically with Croppie

Dynamic Croppie is a simple solution for dynamically cropping images using the Croppie library. This allows users to select an image, dynamically crop it, and obtain the cropped image data in base64 format for further use.

## Prerequisites

Before using Dynamic Croppie, make sure you have the following prerequisites:

- HTML knowledge for integration
- Basic understanding of JavaScript

## Getting Started

1. Include the Croppie library in your project. You can either download the library and include it locally or use a CDN link.

2. Add the necessary HTML code to your web page. Customize the cropping behavior (optional) by modifying the data attributes of the file input (`<input type="file" ...>`):

    - `data-img_prev_selector`: Specifies the selector of the container where the cropped image preview will be displayed.
    - `data-base64_input_selector`: Specifies the selector of the input where the cropped image base64 will be stored for submission.
    - `data-img_width` and `data-img_height`: Set the width and height (in pixels) of the cropped image.
    - `data-img_type`: Specifies the cropping shape ("square" in this example, but you can use "circle" or "rectangle" as well).
    - `data-boundary_width` and `data-boundary_height`: Set the width and height (in pixels) of the cropping boundary.

## Example Usage

Upon selecting an image using the file input, the Croppie library will display a cropping area over the image. Users can adjust the cropping area as desired. When the "Submit" button is clicked (or as per your implementation), the cropped image data in base64 format will be stored in the hidden input field (`<input type="hidden" name="Base64Img" ...>`).

You can then use this data as needed, such as sending it to a server or processing it further in your web application.

## License

Dynamic Croppie is distributed under the [MIT License](LICENSE), which allows you to use, modify, and distribute the code freely.

## Credits

Dynamic Croppie is built using the [Croppie](https://foliotek.github.io/Croppie/) library, which is developed and maintained by Foliotek. Many thanks to the contributors for their valuable work.
