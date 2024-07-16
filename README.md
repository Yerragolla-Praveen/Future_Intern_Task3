## Future_Intern_Task3

## E-commerce Website

#### Overview
This project is a fully functional e-commerce website built with Django. It provides a platform for users to browse and purchase products online, manage their shopping cart, and submit reviews. The application includes robust user authentication, product management features, and a simple cart system that persists user selections.

#### Features
##### User Authentication:

Users can create an account, log in, and log out securely.
Password management with Django's built-in user authentication system.

##### Product Management:

Display a dynamic list of products with sorting options (by price or name).
Filter products based on various criteria, including name and price range.

##### Product Details:

Each product has a dedicated detail page showcasing:
Product image
Detailed description
Price
User reviews and ratings

##### Shopping Cart:

Users can easily add products to their shopping cart.
View cart contents with options to modify item quantities or remove items.
Persistent cart storage across sessions using the database.

##### User Reviews:

Registered users can submit reviews for products they have purchased.
Each review includes a rating and comments, enhancing product insights for future buyers.

##### Interactive User Experience:

Real-time feedback on actions (e.g., adding to cart, submitting reviews) with success/error messages.

##### Technologies Used
Django: The primary web framework used for building the application, providing a robust backend and an ORM for database interaction.
Bootstrap: Utilized for responsive design and modern styling of the frontend, ensuring a visually appealing user interface.
SQLite: The default database used for development. It's lightweight and easy to set up. For production, you can switch to PostgreSQL or any other preferred database.
HTML/CSS: Standard web technologies for the structural layout and styling of the application.
