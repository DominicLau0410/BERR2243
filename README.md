# Ehailing System - My Texi
**My Texi** is a ehailing backend system by using Node.js, Express and MongoDB.
The system supports the full flow of ehailing from booking, ride, payment and rating with role-based access control.


## Features Overview
1. User
- Register & login with JWT authentication
- Manage own profile
- Create, view, update, cancel bookings
- Make payment & rate driver after ride completion


2. Driver
- Register & login with JWT authentication
- Manage own profile
- Register, update, deactivate vehicle
- View available bookings & accept booking
- start & complete ride


3. Admin
- Manage user
- Manage driver
- Manage ride


4. Security
- JWT-based authentication
- Role-based authorization (USER / DRIVER / ADMIN)
- Account status control (active / inactive / suspended)


## Technologies
- Runtime: Node.js
- Framework: Express.js
- Database: MongoDB (native driver)
- Authentication: JWT
- Password Hashing: bcrypt
- Architecture: MVC + Service Layer
- API Style: RESTful API


## Database Design
1. Collection:
- users
- drivers
- admins
- vehicles
- bookings
- rides
- payments
- ratings


2. Entity Relationship Diagram
![Entity Relationship Diagram](<Entity Relationship Diagram.png>)


3. Use Case Diagram
![Use Case Diagram](<Use Case Diagram.png>)


## Future Improvements
- Dynamic distance & fare calculation
- Real-time driver matching
- Customer service
- User, Driver, Admin dashboard & analytics
- Payment gateway integration