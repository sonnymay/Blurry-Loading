# Blurry Loading README

Welcome to the Blurry Loading project! This simple and engaging library allows you to add a dynamic blurry loading effect to your website, providing an interesting visual experience while your content loads. Check out the live demo at: https://sonnymay.github.io/Blurry-Loading/

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Customization](#customization)
- [Browser Support](#browser-support)
- [Contributing](#contributing)
- [License](#license)

## Features

- Dynamic blurry loading effect
- Customizable blur strength and loading duration
- Lightweight and easy to integrate
- Compatible with modern browsers

## Getting Started

1. Clone the repository or download the ZIP file:

   ```sh
   git clone https://github.com/sonnymay/Blurry-Loading.git
   ```

   Or download the ZIP file [here](https://github.com/sonnymay/Blurry-Loading/archive/refs/heads/master.zip).

2. Extract the files and include them in your project folder.

3. Add the following files to your HTML file:

   ```html
   <link rel="stylesheet" href="path/to/Blurry-Loading/css/style.css">
   <script src="path/to/Blurry-Loading/js/main.js"></script>
   ```

## Usage

1. Add a `div` element with the class `loading`:

   ```html
   <div class="loading">
       <!-- Your loading content here -->
   </div>
   ```

2. Customize the loading effect by modifying the `data-*` attributes:

   ```html
   <div class="loading" data-blur-strength="30" data-loading-duration="3s">
       <!-- Your loading content here -->
   </div>
   ```

   Available options include:
   - `data-blur-strength`: The maximum blur strength (default: 30).
   - `data-loading-duration`: The duration of the loading effect (default: "3s").

3. That's it! The Blurry Loading effect will now display on your website.

## Customization

You can customize the appearance of the Blurry Loading effect by modifying the `style.css` file. Here are some common properties you might want to change:

- `loading` - Modify the background color, image, and blur filter properties.
- `content` - Adjust the content font size, color, and other text properties.

## Browser Support

The Blurry Loading library is compatible with the following browsers:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

Please note that the Blurry Loading library may not work correctly on older browsers or those that do not support modern CSS and JavaScript features.

## Contributing

We welcome contributions to the Blurry Loading project. Feel free to submit issues, fork the repository, and create pull requests.

## License

The Blurry Loading library is released under the MIT License. See the [LICENSE](https://github.com/sonnymay/Blurry-Loading/blob/master/LICENSE) file for more information.
