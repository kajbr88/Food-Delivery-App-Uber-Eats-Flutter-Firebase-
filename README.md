# Food Delivery App: Uber Eats Clone (Flutter & Firebase)

This repository contains the Flutter source code for a food delivery application, inspired by Uber Eats. This project is developed while following the "Food Delivery App : Uber Eats (Flutter & Firebase)" course by Sanjay Kumar Das on Udemy.

## Project Overview

This app aims to replicate the core functionalities of a food delivery platform like Uber Eats. It includes features for:

* **Users:**
    * Browsing restaurants
    * Viewing menus
    * Adding items to a cart
    * Placing orders
    * Tracking order status
    * Viewing order history
    * Managing their profile
* **Restaurants:**
    * Managing their menu (adding, editing, deleting items)
    * Receiving new orders
    * Updating order status
* **Delivery Partners:**
    * Viewing available orders
    * Accepting orders for delivery
    * Updating delivery status
    * Viewing delivery history
    * Managing their profile

The backend of the application utilizes Firebase for services such as:

* **Authentication:** User, restaurant, and delivery partner authentication.
* **Firestore:** Realtime database to store application data (restaurants, menus, orders, user information, etc.).
* **Storage:** Storing images (restaurant logos, menu items).
* **Cloud Functions:** Potentially used for more complex backend logic or triggers.
            
## Setup Instructions

To run this application on your local machine, you will need to have Flutter and Firebase set up. Follow these steps:

1.  **Install Flutter:** If you haven't already, install Flutter by following the official installation guide for your operating system: [https://flutter.dev/docs/get-started/install](https://flutter.dev/docs/get-started/install)
2.  **Install Firebase CLI:** You will need the Firebase Command Line Interface to interact with your Firebase project. Install it by following the instructions here: [https://firebase.google.com/docs/cli](https://firebase.google.com/docs/cli)
3.  **Create a Firebase Project:** Go to the Firebase Console ([https://console.firebase.google.com/](https://console.firebase.google.com/)) and create a new project.
4.  **Configure Firebase for Flutter:**
    * **Android:** Follow the instructions to add Firebase to your Android app: [https://firebase.google.com/docs/flutter/setup#android](https://firebase.google.com/docs/flutter/setup#android). This involves downloading the `google-services.json` file and placing it in the `android/app` directory.
    * **iOS:** Follow the instructions to add Firebase to your iOS app: [https://firebase.google.com/docs/flutter/setup#ios](https://firebase.google.com/docs/flutter/setup#ios). This involves downloading the `GoogleService-Info.plist` file and adding it to your Xcode project.
5.  **Enable Firebase Services:** In your Firebase project console, ensure that the following services are enabled:
    * **Authentication:** Choose your desired sign-in methods (e.g., email/password, Google Sign-in).
    * **Firestore:** Create your database. You might need to define initial data structures based on the course content.
    * **Storage:** Enable Firebase Storage.
    * **(Cloud Functions - If used):** Deploy any Cloud Functions as instructed in the course.
6.  **Clone the Repository:** Clone this repository to your local machine:
    ```bash
    git clone https://github.com/kajbr88/Food-Delivery-App-Uber-Eats-Flutter-Firebase-.git
    cd ubereats
    ```
7.  **Get Dependencies:** Navigate to the project directory in your terminal and run:
    ```bash
    flutter pub get
    ```
8.  **Run the Application:** Connect a physical device or start an emulator/simulator and run the app:
    ```bash
    flutter run
    ```

## Key Concepts Learned

### This project helped in understanding and implementing the following key concepts:

* Flutter UI and Design Basics
* Flutter Advanced State management techniques
* Firebase Database Development
* Firebase Authentication
* Google Location services
* Realtime Location Updates
* Google Maps and Map styles
* Calculating Distance and time difference between two points
* Creating Local Notifications
* Processing Task in Background (Thread & Async)
* Loading and Displaying Data
* Save Data Locally on your Device

## Notes
The course is still in progress and I am going to continue updating it.
