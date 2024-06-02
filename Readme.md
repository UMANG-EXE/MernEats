
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
    - Add and manage restaurant Profile and food items.
    - Update order status.

## Screenshots

![homepage-1](https://github.com/UMANG-EXE/MernEats/assets/134010626/d1b472ce-e5b2-4852-9dbf-0dbb8ba7f4aa)
**Fig-1: Homepage**



![User-Pofile Page-2](https://github.com/UMANG-EXE/MernEats/assets/134010626/cb702ee7-65c8-48c0-a87f-9c0925babc6f)
**Fig-2: User Profile Page**



![Restaurants Page-3](https://github.com/UMANG-EXE/MernEats/assets/134010626/dbebfb08-19d0-4fa7-bd76-b08152dce2ce)
**Fig-3: Restaurant Page**



![restaurant-main page-4](https://github.com/UMANG-EXE/MernEats/assets/134010626/2faea44c-faed-4146-ab02-27e60767a01f)
**Fig-4: Restaurant Main Page**



![confirm address page-5](https://github.com/UMANG-EXE/MernEats/assets/134010626/36e7c6a8-bffc-493d-ba04-01f6906fb092)
**Fig-5:  Confirm Address Page**



![payment gatway-6](https://github.com/UMANG-EXE/MernEats/assets/134010626/5a61b07b-9641-4624-82c9-cd0d8453bc5c)
**Fig-6: Payment Gateway**



![order status for customer-7](https://github.com/UMANG-EXE/MernEats/assets/134010626/ca59395d-95fe-404f-a907-a9a19377f862)
**Fig-7: Order Status for Customers**



![manage restaurant  1 -8](https://github.com/UMANG-EXE/MernEats/assets/134010626/74d64e3e-eac8-4371-b3be-f71280df6bd6)
**Fig-8: Manage Restaurant 1**



![manage restaurant  2 -8](https://github.com/UMANG-EXE/MernEats/assets/134010626/b10add95-8678-4a25-8d58-d86cb2fc59b0)
**Fig-9: Manage Restaurant 2**



![manage restaurant  3 -8](https://github.com/UMANG-EXE/MernEats/assets/134010626/09aa7745-db3e-4a00-a8b2-4317ce0d350d)
**Fig-10: Manage Restaurant 3**



![update status-9](https://github.com/UMANG-EXE/MernEats/assets/134010626/7f07a7e0-df65-4e49-9eda-1ab6f3fd2477)
**Fig-11: Update Status**



![order status deliveres-10](https://github.com/UMANG-EXE/MernEats/assets/134010626/b74ee9e0-054a-4112-a305-1bffb18f6bd1)
**Fig-12: Order Status deliveries**

## Contact

For queries, contact Umang at umangjoshi144@gmail.com.
