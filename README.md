# Laravel : Furniture E-commerce website (PWA: Progressive Web App)


## Features :

====== USER =======

   - Login/Register/Logout.
   - Show products with homepage, categories, brands.
   - Product details.
   - Search product with searchbox, tags.
   - Show Product description.
   - Show related products.
   - Product comments.
   - Add, edit to cart.
   - Calculate discount code.
   - Calculate feeship.
   - Show notification (with Toastr.js).
   - Breadcrumb navigation.
   - Product sorting with characters, $price.
   - Show posts with categories posts.
   - Display Website's information.
   - Live Chat with Facebook Messenger Plugin.
   - Social share buttons for each product, each post.
   - Show order history.
   - Print bill for each order.
   - Pagination.

======= ADMIN =======

   - Login/Register/Logout.
   - Show profit with some options (7days ago, month ago, this month, 365days & default: 60days).
   - Show quantities of products, brands, categories.
   - Show views of products, posts.
   - Show quantity of orders.
   - Show order details and approve order.
   - Print bill for each order.
   - CRUD and customize status of products and gallary product's images.
   - CRUD and customize status of categories product.
   - CRUD and customize status of posts.
   - CRUD and customize status of categories post.
   - CRUD and customize status of brands.
   - Customize status and Feedback comments.
   - CRUD and customize status of discount code.
   - CRUD and customize status of slide carousel.
   - Instant search, Multi-column ordering use Datatable.JS.
   - Pagination.
 
 
## Installation :

- Clone the repo and cd into it
- composer install
- Rename or copy .env.example file to .env
- php artisan key:generate
- Set your database credentials in your .env file
- Set your Braintree credentials in your .env file if you want to use PayPal
- Import db file(elaravel.sql) into your database (mysql,sql)
- npm install
- npm run watch
- run command[laravel file manager]:-  php artisan storage:link
- Edit .env file :- remove APP_URL
- php artisan serve or use virtual host
- Visit localhost:8000 in your browser
 
## Screenshots :

### User Part:

![image](https://user-images.githubusercontent.com/85242568/152860342-139b5359-d193-4769-bb11-aee7efb59a4d.png)


### Admin Part:

![image](https://user-images.githubusercontent.com/85242568/152860571-151c75c6-23b4-4c98-90b9-d12d69b18d05.png)
