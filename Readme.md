
# MernEats

MERNeats is an online food ordering application built with the MERN stack and TypeScript. The app allows users to order food from their favorite restaurants by searching for restaurants by name or location. Users can check out and track their order status. Restaurant owners can manage their restaurant's profile, add descriptions, upload images, list food items, and update order statuses. The app uses Okta for authentication, ShadCN/UI for the user interface, Cloudinary for cloud image storage, and Stripe for payments.

## Features

### User Features
- **Search Restaurants**: Users can search for restaurants by name or location.
- **Order Food**: Users can browse food items, add them to their cart, and place orders.
- **Order Tracking**: Users can track the status of their orders (e.g., on the way, delivered).
- **Authentication**: Secure user authentication via Okta.

### Restaurant Owner Features
- **Manage Restaurant Profile**: Owners can add and update their restaurant's description and images.
- **Add Food Items**: Owners can list food items with descriptions and prices.
- **Update Order Status**: Owners can update the status of orders (e.g., on the way, delivered).

## Technology Stack
- **Frontend**: React with TypeScript, ShadCN/UI
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: Okta
- **Image Storage**: Cloudinary
- **Payments**: Stripe

## Getting Started

### Prerequisites
- **Node.js**: Install Node.js from [nodejs.org](https://nodejs.org/)
- **MongoDB**: Set up a MongoDB database
- **Okta Account**: Set up an Okta developer account
- **Cloudinary Account**: Set up a Cloudinary account
- **Stripe Account**: Set up a Stripe account

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/YourGitHubUsername/MERNeats.git
    cd MERNeats
    ```

2. **Install dependencies**:
    ```bash
    # Install backend dependencies
    cd backend
    npm install

    # Install frontend dependencies
    cd ../frontend
    npm install
    ```

3. **Set up environment variables**:
    - Create a `.env` file in the `backend` directory and add the following variables:
        ```plaintext
        MONGO_URI=your_mongodb_connection_string
        OKTA_CLIENT_ID=your_okta_client_id
        OKTA_CLIENT_SECRET=your_okta_client_secret
        OKTA_ISSUER_URI=your_okta_issuer_uri
        CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
        CLOUDINARY_API_KEY=your_cloudinary_api_key
        CLOUDINARY_API_SECRET=your_cloudinary_api_secret
        STRIPE_SECRET_KEY=your_stripe_secret_key
        ```

4. **Run the application**:
    ```bash
    # Run the backend and frontend
    cd backend
    npm run dev

    cd ../frontend
    npm run dev
    ```

### Usage

- **User Flow**:
    - Register or log in using Okta authentication.
    - Search for restaurants by name or location.
    - Browse and order food items.
    - Track the status of your order.

- **Restaurant Owner Flow**:
    - Register or log in using Okta authentication.
    - Add and manage restaurant profile and food items.
    - Update order status.

## Screenshots

![order status deliveres-10](https://github.com/UMANG-EXE/MernEats/assets/134010626/a96dcb03-7f39-4c2d-a881-fe958742ab02)

## Contact

For queries, contact Umang at umangjoshi144@gmail.com.
