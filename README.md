# React Native Wallet

A simple and intuitive expense tracker built with React Native. This app helps you manage your income and expenses on the go, with a clean interface and essential features to keep your finances in check.

This project is divided into two main parts:

* **`mobile/`**: The React Native (Expo) application for iOS and Android.
* **`backend/`**: The Node.js and Express server that powers the app's API.

## Features

* **User Authentication**: Secure sign-up and sign-in functionality using Clerk.
* **Transaction Management**: Easily add, view, and delete your income and expenses.
* **Financial Summary**: Get a quick overview of your total balance, income, and expenses.
* **Cross-Platform**: Runs on both iOS and Android devices.

## Tech Stack

* **Mobile**: React Native, Expo, Clerk
* **Backend**: Node.js, Express, PostgreSQL (Neon)
* **Deployment**: EAS (for mobile), Render (for backend)

## Getting Started

To get the project running locally, you'll need to set up both the mobile app and the backend server.

### Prerequisites

* Node.js and npm (or yarn)
* Expo CLI
* A Clerk account for authentication
* A Neon account for the database

### Setup

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/sampathvenur/react-native-wallet.git
    cd react-native-wallet
    ```

2.  **Set up the backend**:
    * Navigate to the `backend` directory: `cd backend`
    * Install dependencies: `npm install`
    * Create a `.env` file and add your `DATABASE_URL`.
    * Start the server: `npm run dev`

3.  **Set up the mobile app**:
    * Navigate to the `mobile` directory: `cd ../mobile`
    * Install dependencies: `npm install`
    * Create a `.env` file and add your `EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY` and `EXPO_PUBLIC_API_URL`.
    * Start the app: `npx expo`

This will open the Expo developer tools, where you can run the app in a simulator or on your own device using the Expo Go app.
