# mattress-home-api-endpoints
## Main url: 
https://ecommerce-api.event-pulse.com

### Product Endpoints
- **`GET /products/{product}/size/{size}`**
  - Retrieve a product with a specific size and its price.

- **`GET /products/sizes`**
  - Get a list of products with their sizes and prices (available to guests).

- **`GET /products/limit/{limit}`**
  - Retrieve a limited number of products as defined by the `limit` parameter.

- **`GET /products/search/{query}`**
  - Search for products based on a query string.

- **`GET /products/{product}`**
  - Retrieve detailed information about a specific product by its ID.

- **`GET /products`**
  - Retrieve a list of all products.

### Category Endpoints
- **`GET /categories`**
  - Get a list of product categories.
