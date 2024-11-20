
# Ecommerce_APP

A simple e-commerce platform built with **Spring Boot**, **Angular**, and **MySQL** to provide secure and user-friendly online shopping.

---

## Key Features

- **User Management**: Profile creation and account management.
- **Order Tracking**: Real-time updates and notifications for purchases.
- **Product Management**: Add, edit, or remove products with rich details and images.
- **Inventory System**: Real-time stock monitoring and alerts for low inventory.
- **Search Functionality**: Advanced filters.

---

## How to Run the Project

### Prerequisites

Before starting, ensure you have the following installed:

- **Java Development Kit (JDK)** (version 1.8 or higher)
- **Spring Tool Suite (STS)** (or IntelliJ IDEA with Maven support)
- **Maven**
- **Node.js** and **Angular CLI**
- **MySQL Server**

---

### Backend Setup (Spring Boot)

1. **Clone the repository**:
   ```bash
   git clone https://github.com/maram77/Ecommerce_APP.git
   cd Ecommerce_APP/WebProject-BACK-main
   ```

2. **Install dependencies**:
   ```bash
   mvn install
   ```

3. **Update MySQL credentials**:

   Open the `src/main/resources/application.properties` file and update it with your MySQL database credentials:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
   spring.datasource.username=your_username
   spring.datasource.password=your_password
   ```

4. **Run the backend**:
   ```bash
   mvn spring-boot:run
   ```

---

### Frontend Setup (Angular)

1. **Navigate to the frontend folder**:
   ```bash
   cd ../WebProjectFront-main
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the Angular development server**:
   ```bash
   ng serve
   ```

4. **Access the application**:

   Open your browser and navigate to [http://localhost:4200](http://localhost:4200).

---

## Running the Application

Ensure both the backend and frontend are running:

- **Backend**: Accessible at [http://localhost:8080](http://localhost:8080)
- **Frontend**: Accessible at [http://localhost:4200](http://localhost:4200)

---


