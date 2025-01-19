# KICKS - Shoe Selling E-commerce Website

KICKS is an e-commerce website designed to sell shoes, offering users the ability to browse, search, and purchase products securely using VISA and Mastercard payment options. The website is built to be user-friendly, responsive, and efficient for both customers and administrators.

---

## Features

### User Features

- **Product Catalog**: View a wide range of shoes with details such as name, price, size, color, and description.
- **Search and Filters**: Find products easily using search and filter options (e.g., by size, color, or price).
- **Shopping Cart**: Add items to a cart and manage them before proceeding to checkout.
- **Secure Payments**: Complete purchases securely using VISA or Mastercard.
- **Order History**: View past orders and track delivery status.

### Admin Features

- **Product Management**: Add, edit, or remove products from the inventory.
- **Order Management**: View and update order statuses.
- **Customer Management**: Manage user accounts and respond to inquiries.
- **Sales Reports**: View detailed sales analytics.

---

## Tech Stack

### Front End

- **Framework**: React.js / Vue.js
- **Styling**: CSS3, Tailwind CSS / Bootstrap
- **Icons**: FontAwesome / Material Icons

### Back End

- **Framework**: Node.js with Express.js / Django / Laravel
- **Database**: MySQL / PostgreSQL / MongoDB

### Payment Integration

- **Gateway**: Stripe / PayPal / Flutterwave for VISA and Mastercard support

### Hosting

- **Platform**: AWS / Heroku / Vercel / Netlify
- **Domain**: Custom domain configuration

---

## Installation

### Prerequisites

1. **Node.js**: Required for running the backend.
2. **Database**: Set up MySQL/PostgreSQL/MongoDB.
3. **Git**: For cloning the repository.
4. **Payment Gateway Credentials**: Set up an account with Stripe or another gateway and obtain API keys.

### Steps

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/ynewayne/Kicks.git
   cd Kicks
   ```

2. **Install Dependencies**:

   ```bash
   npm install # For backend dependencies
   cd frontend && npm install # For frontend dependencies
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the root and add the following:

   ```env
   DATABASE_URL=your_database_url
   STRIPE_API_KEY=your_stripe_api_key
   STRIPE_SECRET_KEY=your_stripe_secret_key
   ```

4. **Run the Application**:

   - Start the backend:
     ```bash
     npm start
     ```
   - Start the frontend:
     ```bash
     cd frontend && npm start
     ```

5. **Access the Application**:
   Open your browser and navigate to `http://localhost:3000`.

---

## Future Enhancements

- **Add Local Payment Options**: Include mobile money payment methods like M-Pesa for local users.
- **Multi-language Support**: Provide language options for a broader audience.
- **Customer Reviews**: Allow users to review and rate products.
- **AI-Powered Recommendations**: Suggest products based on user preferences and browsing history.

---

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

---

## License

This project is licensed under the MIT License. See the LICENSE file for more information.

---

## Contact

For any inquiries, please contact **Samson Wayne Muhadia** at [muhadiawayne@gmail.com].
