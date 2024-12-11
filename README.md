# HotelManagementSystem<br>

Here’s a README template for your project that includes sections for both React.js (frontend) and Java Spring Boot (backend).<br>

You can customize it further as needed.<br>

Hotel Management System<br>
This project is a Hotel Management System with a React.js frontend and a Java Spring Boot backend.<br>

The Hotel Management System allows hotel administrators to manage bookings, room details, and customer information efficiently. It uses a React.js frontend for user interaction and a Spring Boot backend for handling business logic and APIs.<br>

Technologies Used<br>
Frontend<br>
React.js<br>
HTML5, CSS3, JavaScript<br>
Axios (for API communication)<br>
Backend<br>
Java Spring Boot<br>
Spring Data JPA (for database access)<br>
MySQL / PostgreSQL (database)<br>
Maven (build tool)<br>
Setup Instructions<br>
Backend Setup (Spring Boot)<br>
Clone the repository:<br>


git clone https://github.com/kothavalenilu/HotelManagementSystem.git<br>
cd HotelManagementSystem/backend<br>
Configure the database:<br>

Update application.properties or application.yml with your database credentials:<br>
properties<br>

spring.datasource.url=jdbc:mysql://localhost:3306/hotel_management<br>
spring.datasource.username=root<br>
spring.datasource.password=your_password<br>
spring.jpa.hibernate.ddl-auto=update<br>
Build and run the backend:<br>


mvn clean install<br>
mvn spring-boot:run<br>
Verify backend:<br>
The backend runs on http://localhost:8080.<br>

Frontend Setup (React.js)<br>
Navigate to the frontend folder:<br>


cd frontend<br>
Install dependencies:<br>


npm install<br>
Start the development server:<br>


npm start<br>
Access the frontend:<br>
The React app runs on http://localhost:3000.<br>

Project Structure<br>

HotelManagementSystem/<br>
│<br>
├── backend/<br>
│   ├── src/main/java/com/example/hotelmanagement<br>
│   │   ├── controller/    # REST Controllers<br>
│   │   ├── service/       # Business Logic<br>
│   │   ├── model/         # Entity Classes<br>
│   │   └── repository/    # Database Repositories<br>
│   └── application.properties<br>
│<br>
└── frontend/<br>
    ├── src/<br>
    │   ├── components/    # React Components<br>
    │   ├── pages/         # Pages for routing<br>
    │   ├── services/      # API services using Axios<br>
    │   └── App.js<br>
    └── package.json<br>
API Endpoints<br>
Method	Endpoint	Description<br>
GET	/api/rooms	Get all available rooms<br>
POST	/api/bookings	Create a new booking<br>
GET	/api/bookings/{id}	Get details of a specific booking<br>
PUT	/api/bookings/{id}	Update a booking<br>
DELETE	/api/bookings/{id}	Delete a booking<br>


Screen Shot:<br>
1. Login Page<br>
  
![image](https://github.com/user-attachments/assets/a3163a79-510b-444f-bbb2-047ce952e3cf)<br>

2. Admin Dashbord<br>
![image](https://github.com/user-attachments/assets/0fa8dec1-ef53-475f-be19-eea22b4d5393)<br>

3. Customer Profile<br>
![image](https://github.com/user-attachments/assets/446f39ee-b3d0-4511-8889-5710fd616890)<br>

4. Room Booking Section<br>
![image](https://github.com/user-attachments/assets/c5543eb2-e734-4685-bf45-5bf53e7d08d5)<br>


Contributors <br>

Thank you to the following people for contributing to this project:<br>

- Nilambari Shivmurti Kothavale (kothavalenilu@gmail.com)<br>
- Rohan Somnath Bhoye (rohanbhoye1234@gmail.com)<br>
- Naveen T (naveenfaxy1098@gmail.com)<br>



