# Employee Profile Update System

A ServiceNow-based application designed to simplify employee profile modification requests through a structured HR approval workflow.

## Project Overview

The Employee Profile Update System provides a centralized platform for employees to request changes to their profile information. HR Approvers can review submitted requests and approve or reject them. Approved requests automatically update the corresponding employee profile fields.

## Key Features

- Centralized employee profile management.
- Structured employee profile update requests.
- Automatic submission date and initial status using Business Rules.
- HR approval and rejection using Flow Designer.
- Automated profile updates after approval.
- Rejection message handling.
- Employee and HR Approver roles.
- Configured email notification for new requests.
- Pie chart report for request status analysis.

## Technology Stack

- Platform: ServiceNow
- Development Environment: ServiceNow Studio
- Workflow Automation: Flow Designer
- Business Logic: Business Rules
- Data Management: ServiceNow Tables
- Reporting: ServiceNow Reports
- Access Management: Application Roles

## Application Workflow

1. Employee submits a profile update request.
2. Business Rule initializes the submission date and request status.
3. Flow Designer sends the request for HR approval.
4. HR Approver reviews the request.
5. If approved, the corresponding employee profile field is updated.
6. If rejected, the request status and rejection message are recorded.
7. Request status can be monitored through the report.

## Supported Profile Fields

- Email
- Phone Number
- Department
- Address

## Project Structure

- `screenshots/` – Application screenshots and implementation evidence.
- `documentation/` – Project report, architecture, and ER diagram.
- `README.md` – Project overview and implementation details.
- `ServiceNow-Update-Set.xml` – Optional exported configuration file.

## Limitations

- Complete ACL-based access enforcement requires further configuration and testing.
- Automated Employee Name updates are not implemented.
- Email notification delivery has not been conclusively verified.

## Future Enhancements

- Employee self-service portal.
- Complete role-based access control.
- Dynamic rejection comments.
- Advanced HR analytics dashboard.
- Integration with external HR management systems.

## Author

Arjun Sharma

B.Tech – Computer Science and Engineering  
Chandigarh University
