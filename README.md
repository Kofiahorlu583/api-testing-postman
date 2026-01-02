\# API Testing with Postman \& Newman



Comprehensive REST API testing suite using Postman collections and Newman CLI for automated API validation and CI/CD integration.



\## 🎯 Overview

This project demonstrates API testing best practices using JSONPlaceholder, a fake REST API for testing and prototyping.



\## 🛠️ Tech Stack

\- \*\*Postman\*\* - API testing and development

\- \*\*Newman\*\* - Command-line collection runner

\- \*\*Node.js\*\* - Runtime environment



\## 📋 API Endpoints Tested

| Method | Endpoint | Test Cases |

|--------|----------|------------|

| GET | `/posts` | Status code, array validation, count verification |

| GET | `/posts/1` | Status code, response structure, data validation |

| POST | `/posts` | Create new post, status 201, response validation |

| PUT | `/posts/1` | Update post, status code, data modification |

| DELETE | `/posts/1` | Delete post, status code verification |



\## 🚀 Setup \& Installation



\### Prerequisites

\- Node.js 14.x or higher

\- npm or yarn



\### Installation

```bash

\# Clone repository

git clone https://github.com/Kofiahorlu583/api-testing-postman.git

cd api-testing-postman



\# Install dependencies

npm install

```



\## ▶️ Running Tests



\### Using Newman CLI

```bash

\# Run all tests

npm test



\# Generate HTML report

npm run test:html

```



\### Using Postman Desktop

1\. Import `JSONPlaceholder\_API\_Tests.postman\_collection.json`

2\. Click "Run Collection"

3\. View results in Postman interface



\## 📊 Test Coverage



\### Positive Test Cases

\- ✅ GET all resources successfully

\- ✅ GET single resource by ID

\- ✅ POST create new resource

\- ✅ PUT update existing resource

\- ✅ DELETE remove resource



\### Validation Checks

\- ✅ HTTP status codes

\- ✅ Response structure validation

\- ✅ Data type verification

\- ✅ Required fields presence



\## 📁 Project Structure

```

api-testing-postman/

├── JSONPlaceholder\_API\_Tests.postman\_collection.json

├── package.json

├── reports/

│   └── api-test-report.html

└── README.md

```



\## 🎓 Key Testing Concepts

\- RESTful API testing patterns

\- HTTP methods validation (GET, POST, PUT, DELETE)

\- Status code verification

\- JSON schema validation

\- Automated test execution



\## 📧 Contact

For questions: ahorlukofi335@gmail.com

