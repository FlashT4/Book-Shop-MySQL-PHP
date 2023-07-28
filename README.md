# Book-Shop-MySQL-PHP
Web Development/Technology project 
**Book Shop Website**

This is a simple web application for a bookshop, implemented using PHP, MySQL, HTML, and CSS. It allows users to browse and search for books, add them to their shopping cart, and proceed to checkout. The application also provides an administrative interface for managing the inventory and orders.

## Features

1. **User Registration and Login**: Users can create an account and log in to access the full functionality of the website. Passwords are securely hashed and stored in the database.

2. **Book Catalog**: The website provides a catalog of books, including their titles, authors, descriptions, and prices. Users can browse through the available books, search by title or author, and view detailed information about each book.

3. **Shopping Cart**: Users can add books to their shopping cart while browsing the catalog. The shopping cart keeps track of the selected items, their quantities, and the total price. Users can modify the portions or remove items from the cart.

4. **Checkout Process**: When users are ready to purchase the books in their shopping cart, they can proceed to checkout. The application collects the user's shipping information and displays the final order summary. The payment processing is not implemented in this version and can be added later.

5. **Order Management**: An administrative interface is available for managing the inventory and orders. Administrators can add new books, update their details, and delete books from the catalog. They can also view and manage the list of orders placed by customers.

## Technologies Used

The web application is built using the following technologies:

- **PHP**: The backend logic of the application is implemented using PHP. It handles user authentication, database operations, and business logic.

- **MySQL**: The application uses MySQL as the database management system. It stores information about books, users, orders, and other relevant data.

- **HTML**: The website's front end is created using HTML. It provides the structure and content of the web pages.

- **CSS**: Cascading Style Sheets (CSS) are used to enhance the visual appearance of the website. It defines the layout, colors, fonts, and other design elements.

## Images

![Screenshot 2023-05-17 173031](https://github.com/FlashT4/Book-Shop-MySQL-PHP/assets/70928572/979f0dda-f3ab-4038-88aa-38ca3d7cdc1d)

![Screenshot 2023-05-17 173243](https://github.com/FlashT4/Book-Shop-MySQL-PHP/assets/70928572/59fe85b5-df06-4c20-b2f2-81d45204e77e)

![Screenshot 2023-05-17 173102](https://github.com/FlashT4/Book-Shop-MySQL-PHP/assets/70928572/c7117126-8d9b-4e07-a1b8-9fad96dcfb95)

![Screenshot 2023-05-17 173213](https://github.com/FlashT4/Book-Shop-MySQL-PHP/assets/70928572/b2195fea-be09-444e-8e0b-444b8e06e89e)

## Setup and Usage

To set up the bookshop website on your local machine, follow these steps:

1. Clone the repository from GitHub:

   ```
   git clone https://github.com/FlashT4/Book-Shop-MySQL-PHP.git
   ```

2. Create a new MySQL database and import the SQL dump file provided in the repository.

3. Update the database connection details in the `config.php` file with your database credentials.

4. Launch a local web server or use a development environment like XAMPP or WAMP.

5. Open the website in your web browser and start exploring the book catalog, adding items to the shopping cart, and testing the functionality.

## Future Enhancements

Here are some potential enhancements that can be implemented in the future to improve the bookshop website:

- **User Reviews and Ratings**: Allow users to leave reviews and ratings for books they have purchased or read. Display the average rating for each book.

- **Payment Integration**: Integrate a payment gateway to enable secure online payments for orders.

- **User Profiles**: Provide a user profile section where users can manage their personal information, view order history, and track the status of their orders.

- **Responsive Design**: Make the website responsive to adapt to different screen sizes and devices.

- **Wishlist**: Allow users to create and manage their wishlist of books they are interested in.

- **Discounts and Promotions**: Implement a system to apply discounts and promotional offers to selected books or during specific periods.

## License

This project is licensed under FlashT4. Feel free to modify and use the code for your own purposes.
