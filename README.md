# Image Gallery Web Application

<h3>visit: https://image-gallery-react-01.netlify.app</h3>
<div align="center"> <img alt="alt_text" src="./gallery.gif"/> </div>

## Description:

This is an Image Gallery web application built using React. It displays a collection of images with information about the photographers. The application utilizes the provided `data` array containing image information.

## Features

- **Gallery Component (Gallery.js):** This functional component is responsible for rendering the image gallery on the web page. It maps over the `data` array and displays each image along with the photographer's name.

- **Image Container Styling (styles/style.css):** The CSS file contains styles for the image gallery. It sets up the layout, positioning, and visual effects for the images.

  - The `image-item` class defines the container for each image. It sets a fixed height and width, and the images overflow is hidden to ensure consistent image sizes.
  - The images are scaled to fit the container using the `object-fit: cover` property.
  - Hovering over an image scales it up with a smooth transition effect.

- **App Component (App.js):** The `App` component is the main component of the application. It renders the overall layout of the web page.

- **Main Layout Styling (styles/style.css):** The CSS file sets styles for the main layout of the web page.

  - The `h1` element has a SteelBlue color, centered alignment, and margin adjustments for spacing.
  - The `image-container` class is used to create a flexbox layout to display the images in a responsive grid.

## Project Structure


## Usage

1. The `Gallery` component receives image data from the `data` array and renders the images along with the photographer's name.
2. The `App` component imports the `Gallery` component and displays the image gallery on the web page.

## Image Data

The `data` array contains image information, including the photographer's name and the URL of the large image.

Each image is displayed in the `image-item` container with a smooth hover effect. The `info-name` class provides styling for the photographer's name.

## Screenshots

_[You may include some screenshots of your web application here, showcasing its functionality and design.]_

## Installation

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run `npm install` to install the necessary dependencies.
4. Run `npm start` to start the development server and view the application in your browser.

## Contributing

Contributions are welcome! If you find any bugs or want to suggest new features, please open an issue or create a pull request.


