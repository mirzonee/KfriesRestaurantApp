# KfriesRestaurantApp 🍗🐔🍹 (under development)

This is my Group Project for my Mobile Development (CSC557) coursework. 

Welcome to kfries, your go-to mobile app for discovering and exploring restaurants. This app is specifically designed to enhance customer convenience and satisfaction by allowing users to seamlessly order their food for pickup, saving valuable time by avoiding in-store wait times.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The kfries restaurant app is developed using Android Studio IDE and adheres to the following conditions:

- **Authentication:** The app features login and logout functions. Only registered users can access the mobile app based on their authorizations.

- **Database:** MySQL is used as the database, with pRESTige serving as the backend to provide REST API endpoints.

## Features

- **User Roles:**
  - Customers can log in, create new orders, view order status, cancel orders, and log out.
  - Restaurants can log in, update order status, and log out.

- **Order States:**
  - The order has three states: New (new order), Preparing (restaurant is preparing the dish), Ready (ready for pickup).

- **Additional Customer Features:**
  - Customers can add remarks to their orders.
  - Use SharedPreferences to store login information, allowing users to stay logged in.

- **Additional Restaurant Features:**
  - Restaurants can update the order status to Preparing and Ready.

- **Order Management:**
  - Only orders with a "New" status can be deleted.
  - Display a "Restaurant is busy" message if there are currently more than 10 active orders with a "Preparing" status.

- **Reporting:**
  - Implement reporting functionalities for both customers and restaurants.

- **Mock Payment:**
  - Include mock payment functionalities for a seamless ordering experience.
 
  ## Installation

To get started with kfries on your Android device, follow these steps:

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/kfries-restaurant-app.git
    ```

2. Open the project in Android Studio.

3. Install required dependencies.

4. Run the app on your local emulator or Android device.

## Usage

Once the app is installed and running, use the intuitive interface to log in, create new orders, view order status, and perform other functions based on your role (customer or restaurant).

## Technologies Used

- Android Studio
- React Native
- MySQL
- pRESTige
- [Additional technologies, libraries, or frameworks used]

## Contributing

We welcome contributions from the community! To contribute to kfries, please follow the guidelines outlined in the [Contributing Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

If you have any questions, suggestions, or issues, feel free to reach out:

- Email: your.email@example.com
- Twitter: [@your_twitter_handle](https://twitter.com/your_twitter_handle)
- Submit an issue [here](https://github.com/your-username/kfries-restaurant-app/issues).
