#  Frontend for E-commerce Website

Tech Stack: React, TypeScript, and Redux/Redux Toolkit. Styling: CSS/SASS or MUI.

**Data Sources:**

- Products: id, name, description, categories, variants, sizes
- Categories: id, name
- Orders: id, productId, userId, purchasedAt
- Users: id, firstName, lastName, email, password, role (visitor or admin)

**Pages:**

1. Home page (list all the products)
2. Product page (contain the details of a product)
3. Admin page

**Functionalities for a Visitor:**

- Get list of products
- Filter products by categories or price
- Search products by name
- Add products to a cart
- Remove products from a cart

**Functionalities for an Admin:**

- Add a new product, update info of a product, remove a product

**Authentication:**

- Implement register and login functionality via email and password
- Protect the routes based on login and admin status

**Functionalities for an Admin:**

- list all users, delete or block a user.
- list all orders
- Add a new category, update info of a category, remove a category

**Form Validation**

-  All validations form are Implemented .

### others


- Messages, show loading, success, and error messages (e.g., when loading products list or adding new product)
- Implement pagination feature
- Create a Profile Page (only available if user logs in), implement editing user profile feature (user can change first name, last name)



