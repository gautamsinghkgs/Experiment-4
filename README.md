Node.js Experiments (Exp 4.1, 4.2, 4.3)

This repository contains three Node.js experiments demonstrating CLI programming, REST API development, and concurrency handling using Redis.

📌 Experiment 4.1 – CLI Employee Management System
Aim

To create a simple Command Line Interface (CLI) application to manage employees using Node.js.

Technologies Used

Node.js

Readline module

Features

Add employee

List employees

Exit program

How to Run
node practice.js

🖼 Output Screenshot

📌 Experiment 4.2 – REST API for Playing Card Collection
Aim

To develop a RESTful API using Express.js for managing playing card collections.

Technologies Used

Node.js

Express.js

Postman

API Endpoints

GET /api/cards

POST /api/cards

PUT /api/cards/:id

DELETE /api/cards/:id

🖼 Screenshots
GET Request

POST Request

PUT Request

DELETE Request

📌 Experiment 4.3 – Concurrent Ticket Booking System with Redis
Aim

To implement a concurrent ticket booking system with seat locking using Redis to prevent race conditions.

Technologies Used

Node.js

Express.js

Redis

Artillery (Load Testing)

Features

Seat locking using Redis

Prevents double booking

Handles concurrent requests

Load testing performed with 200 requests

🖼 Screenshots
Redis Running

Booking API Response

Load Test Result

📌 Conclusion

All three experiments were successfully implemented and tested.
Experiment 4.3 demonstrated proper concurrency handling using Redis locking mechanism.

📂 Screenshot Folder Structure

Create a folder named:

screenshots


And add these image files inside:

exp-4.1-output.jpg
get.png
post.png
put.png
redis-running.png
booking-response.png
