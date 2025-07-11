# Innovate

This is a simple **CodeIgniter 3** project with:

- A **POST API** to add products to cart.
- A **GET API** to list cart items with product images.
- A simple **CMS view** to display cart items in a table.

## 📂 Project Structure

- `application/controllers/Cart.php` — Your Cart API controller
- `application/models/Cart_model.php` — Cart DB operations
- `application/views/cart_list.php` — CMS view for cart items
- `application/config/routes.php` — Routing setup

## 🗃️ Database Tables

- `products` — Stores product info
- `product_images` — Stores product images
- `cart` — Stores cart items with user_id

## 🚀 How to Use

1. **POST** to `/index.php/cart/add`  
   Body: `{ "product_id": 1, "quantity": 2 }`

2. **GET** `/index.php/cart/list` — shows cart in JSON

3. **Visit** `/index.php/cart/cart_list` — CMS page to view cart

## 🛠️ Requirements

- PHP 7+
- MySQL
- XAMPP/Laragon/Localhost

---


