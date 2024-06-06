Go EduHub NoSQL
Table of Contents
Overview
Installation
Configuration
Usage
Dependencies
License
Overview
Go EduHub NoSQL is a sample Go application demonstrating MongoDB integration. It provides a RESTful API for managing student data.

Installation
Clone the repository:


git clone https://github.com/yourusername/go_eduhub_nosql.git
cd go_eduhub_nosql
Install the dependencies:

go mod tidy
Configuration
Ensure MongoDB is running on localhost:27017 or update the connection string in main.go.

Usage
Run the application:


go run main.go
The server will start, and the API will be accessible at http://localhost:8080.

Dependencies
MongoDB Go Driver
pq (PostgreSQL driver)
License
This project is licensed under the MIT License.

