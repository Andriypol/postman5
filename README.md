# Cypress Docker Test Automation Project

![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white)

## 📌 Project Overview
REST API Testing using [Postman](https://www.postman.com/), Newman, GitHub Actions and Pages.

## 🛠️ Installation
Ensure you have [Node.js](https://nodejs.org/) installed before proceeding.
#### 1.Clone the repository
```sh
git clone https://github.com/Andriypol/postman5.git
cd postman5
```
#### 2.Install dependencies
```sh
npm install
```

## ▶️ Running Tests

### Run all tests
```sh
npx newman run
```

## 📊 Generating Test Reports
To generate a test report after running tests:
```sh
npx newman run tests/petstore_collection.json -r htmlextra --reporter-htmlextra-export testResults/htmlreport.html --reporter-htmlextra-darkTheme
```
