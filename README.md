# 🛒 Shopping Cart - Spring Boot  

A feature-rich **eCommerce application** built with **Spring Boot 3.0, Spring Security 6.0, Thymeleaf, and MySQL**, offering a smooth shopping experience with authentication, product management, and order processing.

## 🚀 Features  
✅ **User Authentication & Authorization** (Spring Security, JWT)  
✅ **Role-Based Access Control** (Admin & Customer)  
✅ **Product Management** (CRUD operations for products)  
✅ **Shopping Cart Functionality** (Add, Remove, Update items)  
✅ **Order Management** (Checkout, Order History)
✅ **Admin Dashboard** (Manage users, products, and orders)  
✅ **RESTful APIs** (Backend services for data operations)  
✅ **Responsive UI** (Bootstrap for a modern look)  

---

## 🛠️ Tech Stack  

### **Frontend**  
- **HTML, CSS, Bootstrap** (UI Design)  
- **JavaScript** (Client-Side Interactions)  
- **Thymeleaf** (Dynamic Server-Side Rendering)  

### **Backend**  
- **Spring Boot 3.0** (Core Framework)  
- **Spring Security 6.0** (Authentication & Authorization)  

### **Database**  
- **MySQL** (Relational Database for storing user & product data)  

---

## ⚡ Installation & Setup  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/vatsal-30/ecom-spring-mysql.git
cd shopping-cart-spring-boot
```

### **2️⃣ Configure MySQL Database**  
Update `src/main/resources/application.properties`:  
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
```

### **3️⃣ Run the Application**  
```bash
mvn clean install
mvn spring-boot:run
```

### **4️⃣ Access the Application**  
- **Frontend**: `http://localhost:8080/`  
- **Admin Panel**: `http://localhost:8080/Ecommerce_Store` 
