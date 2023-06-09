# Makeup Shop Website

This is a sample website for a makeup shop, built using HTML, CSS, JavaScript, jQuery, Bootstrap, and Gulp.

![Alt text](./assets/images/README.png)

# Features

- Displays products (mascara, bronzer, blush, foundation) for sale in the shop
- Offers a selection of fresh fruit products
- Fetches data from an external API (https://makeup-api.herokuapp.com/) using jQuery
- Allows users to add products to their cart and view their cart
- Uses Bootstrap for responsive design and layout
- Uses Gulp for task automation, including browser syncing, SASS compilation, and minification of CSS and JavaScript files

# Technologies Used

- HTML
- CSS
- JavaScript
- jQuery
- Bootstrap
- Gulp

# API Integration

The website uses the Makeup API to fetch data about Maybelline products and display them on the "Products" page.
This data is fetched using the fetch() function and the response is converted to JSON format using response.json().
The resulting data is then displayed on the page using jQuery, which also allows users to filter products by category and add products to their cart.

# Build Process

To build the website, Gulp is used to automate various tasks such as compiling SASS files, concatenating and minifying CSS and JavaScript files, and refreshing the browser when changes are made.
