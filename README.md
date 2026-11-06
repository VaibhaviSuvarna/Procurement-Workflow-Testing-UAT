# Nexora Procurement Workflow Testing & UAT

## Project Overview

This project demonstrates functional testing and User Acceptance Testing (UAT) for the Nexora Technologies procurement system.

The project focuses on understanding functional requirements, designing test cases, executing tests, documenting results, identifying defects, and recording the final UAT acceptance decision.

Nexora Technologies is a fictional company created for this portfolio project.

## Objective

The objective of this project was to verify that the procurement system meets its defined functional requirements and that the tested workflows are suitable for business use.

The project covers:

- Functional requirements
- Test case design
- Functional test execution
- Test result documentation
- Defect reporting
- User Acceptance Testing
- Final acceptance decision

## Testing Workflow

```text
Functional Requirements
        ↓
Test Case Design
        ↓
Test Execution
        ↓
Pass / Fail Validation
        ↓
Defect Documentation
        ↓
UAT Review
        ↓
Acceptance Decision
```

## Tools Used

- PostgreSQL
- pgAdmin
- Microsoft Excel
- Microsoft Word
- SQL

## Functional Requirements

The Functional Requirement Document covers the following areas:

- Department Management
- Employee Management
- Supplier Management
- Product Management
- Purchase Requisition
- Purchase Order
- Purchase Order Items
- Approval Management

## Test Cases

A total of **15 functional test cases** were created based on the defined requirements.

The test cases include validation of:

- Department records
- Department IDs
- Employee records
- Employee-department relationships
- Supplier records
- Supplier IDs
- Supplier status
- Product records
- Product unit prices
- Purchase requisitions
- Purchase orders
- Purchase order-supplier relationships
- Purchase order items
- PO item quantity and unit price
- Approval records

Detailed test cases are available in:

```text
Testing/Test_Cases.xlsx
```

## Test Execution Results

| Metric | Result |
|---|---:|
| Total Test Cases | 15 |
| Passed | 15 |
| Failed | 0 |
| Blocked | 0 |
| Not Run | 0 |
| Defects | 0 |

All executed test cases passed successfully.

## Bug Reporting

A bug-reporting workbook was prepared to document defects identified during testing.

No defects were identified during the executed testing.

The bug report is available in:

```text
Bug_Reports/Bug_Report.xlsx
```

## User Acceptance Testing

UAT was performed based on the defined functional requirements and the results of the documented functional testing.

The purpose of UAT was to determine whether the tested procurement workflows met the expected business requirements and could be accepted.

### UAT Result

```text
Total Scenarios Evaluated : 15
Passed                    : 15
Failed                    : 0
Blocked                   : 0
Defects                   : 0
UAT Decision              : Accepted
```

The detailed UAT summary is available in:

```text
UAT/UAT_Report.docx
```

```

## FRD, Testing & UAT Relationship

The project follows a simple testing lifecycle:

```text
FRD
↓
Defines what the system should do
↓
Test Cases
↓
Define how the requirements will be verified
↓
Test Execution
↓
Determines whether the functionality works as expected
↓
Bug Report
↓
Documents defects, if any
↓
UAT
↓
Records whether the tested system is acceptable
```

The UAT report does not duplicate all detailed test cases. The detailed testing evidence is maintained separately in the Test Cases workbook.

## Key Learning Outcomes

This project provided practical experience with:

- Functional requirements analysis
- Requirement-to-test mapping
- Test case design
- SQL-based validation
- Functional testing
- Test result documentation
- Defect reporting
- UAT concepts
- Business requirement validation
- Acceptance documentation

## Note

Nexora Technologies is a fictional company created for educational and portfolio purposes.
