# Amazon

![Architecture_Diagram](https://github.com/user-attachments/assets/80223523-730a-487a-b893-1cb211b63f97)


### Feature List
* **Auth Service**
  - **User Registration**: Allows users to register with email and password.
  - **User Login**: Provides authentication using JWT tokens.
  - **Role Management**: Supports admin, seller, and user roles.
  - **User Management**: Admin can manage users and their roles.
* **Product Service**
  - **Product Management**: Sellers can add, update, and delete products.
  - **Inventory Management**: Manage product stock and availability.
  - **Product Search**: Users can search for products by name or category.
  - **Product Details**: Users can view detailed information about products.
* **Order Service**
  - **Cart Management**: Users can add, update, and remove products from their cart.
  - **Order Processing**: Handles order creation, updates, and cancellations.
  - **Payment Integration**: Supports payment processing through third-party services.
  - **Order History**: Users can view their past orders and order details.
* **Notification Service**
  - **Email Notifications**: Sends email notifications for order confirmations, shipping updates, etc.
  - **SMS Notifications**: Sends SMS alerts for important updates.
  - **Event Handling**: Listens to RabbitMQ for events to trigger notifications.
 
