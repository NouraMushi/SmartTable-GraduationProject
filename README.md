# 🖥️ Smart Table Project

## 🎯 Project Goal
The goal of this project is to enhance the quality of service in restaurants and increase customer satisfaction by developing a smart table technology that allows customers to view menus, place orders, and make payments through a touch screen.

## 📝 Project Description and Implementation
The project involves developing an integrated system consisting of two main applications: one for customers and one for staff, supported by the necessary hardware to achieve the desired objective.

### 📱 Customer Application
- **Menu Display:** The menu is displayed on a touch screen that customers can easily use to browse available options.
- **Order Placement:** Customers can select orders directly from the screen and send them to the kitchen.
- **Electronic Payment:** The application allows customers to make payments online using credit cards or PayPal accounts.

#### 📱 Customer Application Screenshots

<div align="center">
  <img src="https://github.com/user-attachments/assets/edd67e33-fbb8-4dcd-a9d5-2d839f883a23" width="300" height="200" style="margin: 5px;">
  <img src="https://github.com/user-attachments/assets/621fe4d6-a7e7-403b-9ccc-3d840af892d1" width="300" height="200" style="margin: 5px;">
  <img src="https://github.com/user-attachments/assets/0045e8b8-91cf-47de-9867-b55186f940cd" width="300" height="200" style="margin: 5px;">
  <img src="https://github.com/user-attachments/assets/82da2042-9c94-44b6-bdfb-c325f45e55ea" width="300" height="200" style="margin: 5px;">
  <img src="https://github.com/user-attachments/assets/8dc11536-ea0b-4344-b255-5ecd81264d17" width="300" height="200" style="margin: 5px;">
  <img src="https://github.com/user-attachments/assets/c7c0c121-9ade-4dfd-b5af-715ba3f03d7d" width="300" height="200" style="margin: 5px;">
  <img src="https://github.com/user-attachments/assets/67a47ce4-f0f1-495e-96db-6e1aa2b3ca3e" width="300" height="200" style="margin: 5px;">
  <img src="https://github.com/user-attachments/assets/eed4c0fb-3b57-4374-9d1e-db435f4830e6" width="300" height="200" style="margin: 5px;">
  <img src="https://github.com/user-attachments/assets/5b6bb2fe-e9ff-4f09-9446-708d7304ad59" width="300" height="200" style="margin: 5px;">
</div>


### 👨‍🍳 Staff Application
- **Chef Interface:** Displays incoming orders from customers, allowing the chef to prepare and confirm orders.
- **Waiter Interface:** Shows ready-to-serve orders, making it easier for waiters to deliver food quickly and efficiently.
- **Table and Staff Management:** Allows the manager to create staff accounts, assign tables, and modify or delete information as needed.

#### 👨‍🍳 Staff Application Screenshots

<div align="center">
  <img src="https://github.com/user-attachments/assets/79d78631-83ec-4ca7-9ec8-042bade4182e" width="300" height="200">
  <img src="https://github.com/user-attachments/assets/6412c272-0dc3-4c95-91be-4292b4574f36" width="300" height="200">
  <img src="https://github.com/user-attachments/assets/3ec156a6-ebb5-4a4f-bd78-efc4df6d018b" width="300" height="200">
  <img src="https://github.com/user-attachments/assets/6925efcb-4cca-4d9c-817b-3fb125b5f495" width="300" height="200">
  <img src="https://github.com/user-attachments/assets/6ea34dc9-2137-4e3c-87fe-926f07dfdef7" width="300" height="200">
</div>

## 💻 Technologies Used
- **Android Studio:** For developing mobile applications for customers and staff.
- **ESP8266:** To enable communication between the customer application and various devices like motion sensors and touch screens.
- **Firebase:** For providing backend services like real-time database, cloud storage, and authentication.
- **Arduino:** For developing and programming the electronic boards used in the system.
- **Flutter:** For cross-platform mobile application development.
- **StarUML:** For designing models and software elements.

## 🏗️ Architectural Design
The Smart Table project relies on both hardware and software components. The main components include:
<div align="center">
  <img src="https://github.com/user-attachments/assets/ae3036ed-5e9f-4567-84a7-71fb63c661fd"width="300" height="200">
</div>

### 🔧 Hardware
- **ESP8266:** Microcontroller for Wi-Fi communication.
- **Motion Sensor (IR):** Detects customer presence.
- **Touch Screen (LCD):** Displays menu and receives customer input.

### 💾 Software
- **Android Application:** Developed using Android Studio, connected to ESP8266 to control devices.

## ⚙️ Implementation Steps
1. **Connecting Devices:** The motion sensor (IR) is connected to the ESP8266. When motion is detected, the touch screen welcomes the customer and displays the menu.
2. **Placing Orders:** Customers select orders from the screen, which are sent directly to the database in the cashier device.
3. **Preparing Orders:** Orders are displayed on the kitchen screen, where the chef prepares and confirms them.
4. **Serving Orders:** Waiters are notified of ready orders via the staff application.
5. **Payment and Review:** Customers can make electronic payments and submit reviews through the application.

## ✨ Conclusion
Thank you for exploring the Smart Table project! This project showcases the integration of technology to enhance dining experiences and streamline restaurant operations.


**Noura Abdullah** , **Wadha Almutairi**
