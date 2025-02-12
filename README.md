# Azo Gebeya

Azo Gebeya is a Next.js-based e-commerce platform tailored for Ethiopia. It provides a seamless online shopping experience, connecting buyers and sellers with a user-friendly interface and efficient transaction processing.

## Features

- **User Authentication:** Secure login and registration system.
- **Product Listings:** Display various products with descriptions, images, and prices.
- **Cart and Checkout:** Add items to cart and proceed to checkout seamlessly.
- **Payment Integration:** Supports multiple payment methods, including local Ethiopian options.
- **Order Management:** Track order status and history.
- **Admin Dashboard:** Manage products, users, and transactions efficiently.
- **Mobile Responsive:** Optimized for both desktop and mobile devices.

## Technologies Used

- **Frontend:** Next.js, React, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** Firebase/Auth0
- **Payment Gateway:** Chapa/Flutterwave
- **Hosting:** Vercel/AWS

## Installation & Setup

### Prerequisites

Ensure you have the following installed:

- Node.js (v18+)
- MongoDB
- Git

### Steps

1. Clone the repository:
   ```sh
   git clone https://github.com/ZekariyasT/azo-gebeya.git
   cd azo-gebeya
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create a `.env.local` file and add the required environment variables:
   ```sh
   NEXT_PUBLIC_API_URL=<your-api-url>
   DATABASE_URL=<your-mongodb-connection-string>
   NEXT_PUBLIC_FIREBASE_API_KEY=<your-firebase-api-key>
   ```
4. Start the development server:
   ```sh
   npm run dev
   ```
   The app will be available at `http://localhost:3000`

## Contribution

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`feature-branch-name`).
3. Commit changes and push to your fork.
4. Open a pull request.

## Contact

For inquiries, reach out via [zekariyastesfayedesta@gmail.com] .
