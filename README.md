[![API Tests](https://github.com/abpati1005/api-automation-framework/actions/workflows/api-tests.yml/badge.svg?branch=main)](https://github.com/abpati1005/api-automation-framework/actions)
# API Automation Framework (Postman + Newman)

## 📌 Project Overview

This project demonstrates API automation using Postman and Newman CLI.
It includes automated CRUD testing using Swagger Petstore APIs.

## 🚀 Tech Stack

* Postman
* Newman
* Node.js
* GitHub
* CLI Automation

## 📂 Project Structure

```
api-automation-framework
│
├── collections
│   └── swagger-petstore-collection.json
│
├── environments
│
├── scripts
│
├── test-data
│
├── reports
│
├── .gitignore
└── README.md
```

## ▶️ How to Run Tests

```bash
newman run collections/swagger-petstore-collection.json
```

## 📊 Generate HTML Report

```bash
newman run collections/swagger-petstore-collection.json -r html --reporter-html-export reports/report.html
```

## ✅ Test Coverage

* Create Pet (POST)
* Get Pet (GET)
* Update Pet (PUT)
* Delete Pet (DELETE)
* Validate Deleted Pet (404)

## 🎯 Features

* CLI execution
* HTML reporting
* GitHub integration
* Scalable framework structure

## 👨‍💻 Author

Abhishek Patil
