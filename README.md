# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

/my-react-app
|-- /src
    |-- /components
    |   |-- Navbar.js               # Component for the navigation bar
    |   |-- SearchBar.js            # Component for the search functionality
    |   |-- Banner.js               # Component for the main banner
    |   |-- Logo.js                 # Component for the site logo
    |   |-- ProductList.js          # Component to display a list of products
    |   |-- ProductItem.js          # Component for each product in the list
    |   |-- Cart.js                 # Component for the shopping cart
    |   |-- CheckoutForm.js         # Component for the checkout form
    |   |-- Footer.js               # Component for the footer
    |
    |-- /pages
    |   |-- HomePage.js             # Main landing page of the site
    |   |-- ProductPage.js          # Page to display individual product details
    |   |-- CartPage.js             # Page for reviewing the shopping cart
    |   |-- CheckoutPage.js         # Page for the checkout process
    |   |-- LoginPage.js            # Page for user login
    |   |-- RegisterPage.js         # Page for new user registration
    |
    |-- /api
    |   |-- index.js                # Central file to manage API calls
    |   |-- products.js             # API calls related to products
    |   |-- users.js                # API calls related to user authentication
    |   |-- cart.js                 # API calls for cart management
    |
    |-- /services
    |   |-- productService.js       # Service functions for product-related operations
    |   |-- authService.js          # Service functions for authentication-related operations
    |   |-- cartService.js          # Service functions for cart-related operations
    |
    |-- /context
    |   |-- UserContext.js          # Context for user authentication state
    |   |-- CartContext.js          # Context for cart state
    |
    |-- /utils
    |   |-- formatPrice.js          # Utility for formatting prices
    |   |-- validateInput.js        # Utility for validating form inputs
    |   |-- storage.js              # Utility for managing local storage
    |
    |-- /styles
    |   |-- main.css                # Main stylesheet for the application
    |   |-- navbar.css              # Styles for the Navbar component
    |   |-- banner.css              # Styles for the Banner component
    |   |-- logo.css                # Styles for the Logo component
    |   |-- product-list.css        # Styles for the ProductList component
    |   |-- footer.css              # Styles for the Footer component
    |
    |-- App.js                      # Main application component
    |-- index.js                    # Entry point for the React application
    |-- ...

# Backend will be like this
/my-ecommerce-app-backend
|-- /controllers       # Business logic handlers for various routes
|-- /routes            # API route definitions
|-- /models            # Database models
|-- /services          # Business logic, including interaction with Kroger API
|-- /middlewares       # Authentication and other middleware
|-- /config            # Configuration files and environment variables
|-- /utils             # Utility functions
|-- /tests             # Test files for your backend application
|-- app.js             # Main application file to set up server
|-- ...
