# exam-4-intern


### Project Overview
Create a shopping app where users can browse products, add them to a cart, and place orders. The frontend will use React, and the backend will use Node.js and Express with MongoDB as the database.

### Requirements

#### Frontend (React)
1. **Setup and Structure**
   - Use `create-react-app`.
   - Organize folders for components, services, contexts, and styles.

2. **Components**
   - **Product List**: Display all products.
   - **Product Details**: Show product details with an add-to-cart button.
   - **Shopping Cart**: Display and manage cart items.
   - **Checkout Form**: Capture user details for orders.

3. **State Management**
   - Use React hooks (useState, useEffect, useContext).
   - Manage global state with Context API or Redux.

4. **API Integration**
   - Create a service layer for API requests.
   - Implement CRUD operations for products and cart items.

5. **Authentication**
   - Implement sign-up, login, and logout using JWT.

6. **Styling**
   - Use CSS or styled-components.
   - Ensure responsive design.

7. **Error Handling**
   - Display error messages for API failures and form validation.

8. **Testing**
   - Write unit tests using Jest and React Testing Library.

#### Backend (Node.js & Express)
1. **Setup**
   - Use `npm init` and install necessary packages (express, mongoose, body-parser, cors, bcrypt, jsonwebtoken).

2. **API Endpoints**
   - **User Authentication**: Sign-up, login, logout.
   - **Products**: CRUD operations.
   - **Cart**: Add, update, remove items.
   - **Orders**: Place orders and fetch user orders.

3. **Database**
   - Use MongoDB with Mongoose.
   - Define models for User, Product, CartItem, and Order.

4. **Middleware**
   - Use body-parser, CORS, and authentication middleware.

5. **Error Handling**
   - Handle and return appropriate HTTP status codes and validation errors.

6. **Testing**
   - Write unit tests for API endpoints using Mocha or Jest.

### Sample Questions

#### React (Frontend)
1. **Setup and Structure**
   - How would you set up and organize a React project?

2. **Components**
   - How would you design a Product List and Shopping Cart component?

3. **State Management**
   - How would you manage global state with Context API or Redux?

4. **API Integration**
   - How would you handle asynchronous API calls and update the UI?

5. **Authentication**
   - How would you implement user authentication with JWT?

6. **Styling**
   - How would you ensure the app is responsive and styled properly?

7. **Error Handling**
   - How would you handle and display errors for API failures and form validation?

8. **Testing**
   - How would you write unit tests for components?

#### Node.js & Express (Backend)
1. **Setup**
   - How would you set up a Node.js project and necessary packages?

2. **API Endpoints**
   - How would you design and implement the API endpoints for products and user authentication?

3. **Database**
   - How would you define and interact with MongoDB models?

4. **Middleware**
   - How would you implement middleware for body parsing, CORS, and authentication?

5. **Error Handling**
   - How would you handle and return errors and validation issues?

6. **Testing**
   - How would you write unit tests for API endpoints?

### Deliverables
1. **Frontend**: Source code, setup instructions, and unit tests.
2. **Backend**: Source code, setup instructions, and unit tests.
3. **Documentation**: Detailed README and API documentation.

### Evaluation Criteria
1. **Code Quality**: Clean, readable code and proper state management.
2. **Functionality**: All features work correctly, with proper error handling.
3. **Testing**: Adequate test coverage with passing tests.
4. **User Interface**: User-friendly, responsive, and intuitive design.

This simplified version outlines the key requirements and questions for testing an intern's skills in building a shopping app using React and Node.js.
