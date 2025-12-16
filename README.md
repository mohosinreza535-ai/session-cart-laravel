# session-cart-laravel
A simple Laravel-based mini e-commerce application using session for cart management. Supports product listing from database, single product view, add/remove cart functionality, and checkout.
# Laravel Mini E-Commerce

## Description
This is a simple e-commerce application built with Laravel. It uses sessions to manage the shopping cart instead of storing cart data in the database. Products are fetched from a MySQL database.

## Features
- Product listing from database
- Single product view
- Add to cart & remove from cart
- Checkout (session clear after order)
- Easy to extend and customize

## Tech Stack
- Laravel
- PHP
- MySQL
- Bootstrap (optional for styling)

## Installation
1. Clone the repo
2. Run `composer install`
3. Copy `.env.example` to `.env` and configure database
4. Run `php artisan migrate --seed`
5. Start server: `php artisan serve`

## License
MIT
