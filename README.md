# 🍕 Food Delivery Mobile App

A comprehensive, multi-role food delivery platform built with React Native and Expo. This application serves three distinct user types: Customers, Restaurant Owners, and Delivery Drivers, each with their own specialized interface and features.

## 🎯 App Overview

This is a complete food delivery ecosystem that connects customers, restaurants, and delivery drivers in one seamless platform. Users can choose their role upon signup and access role-specific features designed for their needs.

## 👥 User Roles & Features

### 🛍️ Customer Features

**Authentication & Profile**
- Sign up and login as a customer
- Manage profile information (name, email, address)
- View order statistics (total orders, favorites, reviews)
- Save favorite restaurants and menu items

**Browse & Order**
- Browse restaurants by categories (Breakfast, Lunch, Dinner, Desserts)
- Search for specific foods or restaurants
- View special offers and discounts (e.g., "30% OFF on your first order")
- Filter by cuisine type (Burgers, Pizzas, Burritos, etc.)
- View detailed menu items with photos and prices
- Add items to cart with quantity selection
- Apply discounts and view order summary

**Order Management**
- Place orders with real-time order tracking
- View order history with detailed receipts
- Track delivery status in real-time
- Contact delivery driver directly
- Navigate to order location via GPS integration

### 🍳 Restaurant Owner Features

**Account Management**
- Sign up and login as restaurant owner
- Create and manage restaurant profile with photos
- Add restaurant description and details
- View restaurant statistics dashboard
- Monitor daily overview (orders, revenue, ratings)

**Menu Management**
- Create and organize menu categories
- Add new dishes with photos and descriptions
- Set and update dish prices
- Edit or remove menu items
- Manage signature dishes collection
- View dish ratings and reviews

**Order Processing**
- Receive incoming order notifications
- View order details and customer information
- Accept or reject orders
- Update order preparation status
- Manage active, new, and preparing orders
- Kitchen display system for order tickets

### 🚴 Delivery Driver Features

**Driver Account**
- Sign up and login as delivery driver
- Manage driver profile with verification status
- Enter driver secret code for authentication
- View driver statistics (deliveries, earnings, ratings)

**Delivery Management**
- View available delivery orders in real-time
- Accept delivery requests
- View pickup location and customer delivery address
- Navigate to restaurant for pickup
- Navigate to customer location via GPS
- Call customers directly from the app
- Track delivery history and earnings
- View weekly statistics (deliveries, earnings, time)

## 📸 App Screenshots
you can see the app screenshots in the screenshots folder

## 🎨 Key Features Showcase

- **Multi-role Authentication**: Separate signup flows for customers, restaurant owners, and delivery drivers
- **Real-time Order Management**: Live updates for order status across all user types
- **GPS Integration**: Navigation for delivery drivers to find restaurants and customers
- **Kitchen Display System**: Restaurant owners receive and manage orders via ticket system
- **In-app Communication**: Direct calling between drivers and customers
- **Payment Summary**: Detailed breakdown of order costs, delivery fees, and discounts
- **Statistics Dashboard**: All users have access to personalized stats and metrics
- **Search & Filter**: Advanced search with category filters for easy food discovery
- **Special Offers**: Promotional banners and discount systems for customers

- **Framework**: React Native with Expo
- **Language**: TypeScript
- **Styling**: NativeWind (Tailwind CSS for React Native)
- **Navigation**: Expo Router
- **State Management**: Zustand/Redux (based on store directory)
- **Development Tools**: ESLint, Babel

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (v14 or higher)
- npm or yarn
- Expo CLI (`npm install -g expo-cli`)
- iOS Simulator (for Mac users) or Android Studio (for Android development)

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/arouedkhelifi/food_delivery_mobile_app.git
   cd food_delivery_mobile_app
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables**
   
   Create a `.env` file in the root directory and add your configuration:
   ```env
   API_URL=your_api_url_here
   # Add other environment variables as needed
   ```

4. **Start the development server**
   ```bash
   npx expo start
   ```

## 📱 Running the App

### iOS
```bash
npx expo start --ios
```
Or press `i` in the terminal after running `npx expo start`

### Android
```bash
npx expo start --android
```
Or press `a` in the terminal after running `npx expo start`

### Web (if supported)
```bash
npx expo start --web
```
Or press `w` in the terminal after running `npx expo start`

## 📁 Project Structure

```
food_delivery_mobile_app/
├── app/                 # App screens and routes (Expo Router)
├── assets/             # Images, fonts, and other static assets
├── components/         # Reusable UI components
├── constants/          # App constants and configuration
├── lib/               # Utility functions and helpers
├── store/             # State management (Zustand/Redux)
├── .env               # Environment variables
├── app.json           # Expo configuration
├── package.json       # Dependencies and scripts
├── tailwind.config.js # Tailwind/NativeWind configuration
└── tsconfig.json      # TypeScript configuration
```

## 🎨 Key Components

- **Navigation**: Built with Expo Router for seamless screen transitions
- **UI Components**: Custom, reusable components for consistent design
- **State Management**: Centralized state handling for cart, user, and app data
- **Styling**: Utility-first styling with NativeWind

## 🔧 Available Scripts

- `npm start` - Start the Expo development server
- `npm run android` - Run on Android emulator/device
- `npm run ios` - Run on iOS simulator/device
- `npm run web` - Run in web browser
- `npm run lint` - Run ESLint for code quality checks

## 🌟 Features in Development

- Payment integration (Stripe/PayPal)
- Push notifications for order updates
- Advanced analytics dashboard for restaurant owners
- Rating and review system enhancements
- Multi-language support
- Dark mode theme
- Loyalty rewards program

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request



⭐ If you found this project helpful, please give it a star!
