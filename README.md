# DummyJSON REST API Testing Project

A professional **Manual REST API Testing Portfolio Project** built using **Postman** and **Newman** to validate the functionality of the DummyJSON REST API.

This project demonstrates practical QA documentation, organized API testing and real-world testing scenarios suitable for a **Junior SQA Engineer Portfolio**.

---

## Project Overview

The project focuses on validating REST API functionality through manual testing.

The testing includes:

* Authentication
* CRUD Operations
* Product APIs
* Cart APIs
* User APIs
* Search Functionality
* Negative Testing
* Response Validation
* Newman HTML Reporting

---

## Tools Used

| Tool           | Purpose                  |
| -------------- | ------------------------ |
| Postman        | API Testing              |
| Newman         | Collection Execution     |
| DummyJSON      | REST API                 |
| Excel          | Test Cases & Bug Reports |
| Microsoft Word | Test Plan                |
| GitHub         | Portfolio Hosting        |

---


## Modules Covered

### Authentication

- Login User
- Get Current User
- Token Validation

### Products

- Get All Products
- Get Single Product
- Add Product
- Update Product
- Delete Product
- Search Product
- Categories
- Sorting

### Cart

- Get Cart
- Add Cart
- Update Cart
- Delete Cart

### Users

- Get All Users
- Get Single User
- Search User
- Update User
- Delete User

### Negative Testing

- Wrong Login
- Invalid Product
- Invalid User
- Invalid Cart
- Wrong Endpoint
- Wrong Method
- Blank Search


---


## Test Deliverables

### Postman Collection

Contains all API requests and test scripts.

### Environment File

Contains reusable variables.

### Manual Test Cases

40 professionally documented test cases.

### Bug Report

10 Jira-style bug reports with severity and priority.

### Test Plan

IEEE-style professional test plan.

### Newman Report

HTML execution report generated using Newman.


---

## Project Structure

```text
dummyjson-api-testing-project/
│
├── Postman/
│   ├── S-Dummy.postman_collection.json
│   └── S-Dummy.postman_environment.json
│
├── Documentation/
│   └── S-Dummy_Test_Plan_IEEE_Style.docx
│
├── Test_Cases/
│   └── S-Dummy_JSON_Test_Cases_Professional_v2.xlsx
│
├── Bug_Reports/
│   └── S-Dummy_Bug_Report_Professional_v2.xlsx
│
├── Newman_Report/
│   └── newman-report.html
│
├── Screenshots/
│
└── README.md
```

---

## Testing Workflow

1. Import the Postman Collection.
2. Import the Environment.
3. Execute the Login request.
4. Capture the Bearer Token.
5. Execute all API modules.
6. Run Negative Test scenarios.
7. Validate responses and status codes.
8. Generate the Newman HTML Report.
9. Prepare QA documentation.

---

## Newman Execution

Run the collection using Newman.

```bash
newman run Postman/S-Dummy.postman_collection.json \
-e Postman/S-Dummy.postman_environment.json \
-r htmlextra \
--reporter-htmlextra-export Newman_Report/newman-report.html
```

The generated HTML report includes:

* Request Summary
* Passed & Failed Assertions
* Response Time
* Status Codes
* Request Details

---

## Key Skills Demonstrated

* Manual API Testing
* REST API Validation
* Authentication Testing
* CRUD Testing
* Negative Testing
* Postman Variables
* Test Case Design
* Bug Reporting
* Newman Report Generation
* QA Documentation


---

## Future Improvements

- Data Driven Testing
- Newman Automation
- GitHub Actions Integration
- API Schema Validation
- Automated API Testing


---

## Author

**Mahbub Sourov**

Aspiring **Junior SQA Engineer** focused on Manual Testing, API Testing and QA Documentation.

---

## License

This project is shared for educational and portfolio purposes.
