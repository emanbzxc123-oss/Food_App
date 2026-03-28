# Food Ordering App

A mobile food ordering application developed using Flutter for the frontend and PHP + MySQL for the backend API. This app allows users to browse food items, add them to a cart, and place orders seamlessly.

---

## Features

- User Authentication (Login and Register)
- View Food Menu from API
- Add to Cart
- Update Quantity in Cart
- Checkout and Order Submission
- Order Success Page
- Order History Page
- Modern UI Design

---

## Technologies Used

- Frontend: Flutter (Dart)
- Backend: PHP (REST API)
- Database: MySQL
- Server: XAMPP (Apache)

---

## Requirements

- Flutter SDK
- Android Studio or VS Code
- XAMPP (Apache and MySQL)
- Android Emulator or Physical Device

---

## How to Run the Application

### 1. Clone the Repository

git clone https://github.com/emanbzxc123-oss/Food_App.git  
cd Food_App

---

### 2. Install Dependencies

flutter pub get

---

### 3. Setup Database

- Open XAMPP  
- Start Apache and MySQL  
- Go to phpMyAdmin  
- Create database:  

food_app_db  

- Import your SQL tables (users, foods, orders, order_items)

---

### 4. Setup Backend API

Place your PHP files in:

C:\xampp\htdocs\food_api\

---

### 5. Configure API URL

For emulator:
http://10.0.2.2/food_api  

For real device:
http://YOUR-PC-IP/food_api  

---

### 6. Run the App

flutter run

---

## Important Notes

- Make sure your phone and PC are on the same Wi-Fi  
- Start Apache and MySQL before running  
- Ensure correct API URL  

---

## Author

- Eman Briones

---

## License

- For educational purposes only
