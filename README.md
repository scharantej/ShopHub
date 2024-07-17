## Flask Application Design for Craft an e-commerce website that offers a variety of products. Implement a user-friendly interface that provides a personalized shopping experience. Ensure easy navigation and a seamless checkout process.

## HTML Files

### home.html
- Homepage of the e-commerce website.
- Displays a list of featured products along with their images, titles, prices, and "Add to Cart" buttons.
- Contains a search bar for customers to find specific products.

### product_detail.html
- Page for displaying detailed information about a particular product.
- Includes product title, description, images, reviews, and "Add to Cart" button.

### cart.html
- Shows the items currently in the user's shopping cart.
- Provides options to update quantities, remove items, and proceed to checkout.

### checkout.html
- Checkout page where the customer can review their order, choose a payment method, and provide shipping information.

### order_confirmation.html
- Confirmation page displayed after a successful order placement.
- Shows the order details, estimated delivery time, and tracking information.

## Routes

### Main Routes
- `/` - Renders the homepage (home.html).
- `/products` - Displays a catalog of all products.
- `/product/<product_id>` - Renders the detailed product page (product_detail.html).
- `/cart` - Shows the shopping cart (cart.html).
- `/checkout` - Renders the checkout page (checkout.html).
- `/order-confirmation` - Displays the order confirmation page (order_confirmation.html).

### API Routes
- `/api/products` - API endpoint to fetch a list of products.
- `/api/products/<product_id>` - API endpoint to retrieve a specific product.
- `/api/cart` - API endpoint to manage the shopping cart, including adding, removing, and updating items.
- `/api/orders` - API endpoint to create and retrieve orders.
- `/api/payments` - API endpoint for processing payments.