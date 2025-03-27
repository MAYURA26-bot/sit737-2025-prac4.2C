#  Enhanced Calculator Microservice

This project implements an **enhanced calculator microservice** using **Node.js** and **Express.js**, built as part of SIT737 – Cloud-Native Application Development (Task 4.2C). It supports both basic and advanced arithmetic operations through a responsive, web-based calculator UI and RESTful API endpoints.


##  Features

-  Basic Operations: Addition, Subtraction, Multiplication, Division
-  Advanced Operations: Modulo (%), Power (^), Square Root (√)
-  Modern Calculator-style UI using HTML + Bootstrap
-  RESTful API endpoints for each operation
-  Error handling for:
   - Invalid inputs
   - Division or modulo by zero
   - Square root of negative numbers
-  Winston-based logging:
   - All operations and results (info level)
   - All errors (error level)
   - Logs stored in `logs/combined.log` and `logs/error.log`

### Prerequisites
- [Node.js](https://nodejs.org/en/) installed
- [Git](https://git-scm.com/) installed

  ### Installation
- git clone https://github.com/yourusername/sit737-2025-prac4c.git
- cd sit737-2025-prac4c
- npm install

