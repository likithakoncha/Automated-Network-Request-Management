# Automated-Network-Request-Management
Automated Network Request Management system developed using ServiceNow to streamline network request submission, validation, approval, and notification processes.
## 📌 Project Overview
The Automated Network Request Management system provides a structured way for users to submit network-related requests through the ServiceNow Service Catalog.
The project uses ServiceNow configuration, Service Catalog, client-side logic, Flow Designer, approvals, and email notifications to automate the request management process.

## 🔹 Phase 1 – Service Catalog & Request Configuration
In Phase 1, a custom **Network Request** catalog item was created in ServiceNow to collect network-related information from users.
The catalog item includes variables such as Request Type, IP Address, Network Type, Urgency, Network Location, Business Justification, and Description.
User groups and appropriate access configurations were also considered for Requesters, Approvers, and the Network Team.
The configured catalog item allows users to submit structured network service requests through the Service Catalog.

## 🔹 Phase 2 – Dynamic Form & Request Validation
In Phase 2, client-side logic was implemented to improve the user experience of the Network Request form.
The form dynamically displays or controls fields based on the selected network request type.
Mandatory fields and appropriate validations were configured to ensure that users provide the required information before submitting a request.
This phase helps maintain accurate and consistent network request data.

## 🔹 Phase 3 – Workflow Automation & Approvals
In Phase 3, the network request processing workflow was configured using **ServiceNow Flow Designer**.
The workflow manages the request after submission and supports the approval and processing stages.
Approval-related actions and request status updates were configured to automate the request management process.
This reduces manual processing and provides a structured workflow from request submission to completion.

## 🔹 Phase 4 – Notifications, Testing & Final Validation
In Phase 4, email notifications and final workflow validation were completed.
The system was tested by submitting network requests and verifying request creation, approval processing, workflow execution, and notification generation.
The final testing confirmed that the configured components work together as an automated network request management process.
Screenshots and supporting documentation were prepared as evidence of the completed implementation.

📚 Project Documentation
The complete documentation for all four phases is available through the Google Drive link below.
👉 View Complete Project Documentation
[Replace YOUR_GOOGLE_DRIVE_LINK_HERE with your actual Google Drive documentation link.](https://drive.google.com/drive/folders/1RE7_RZg78ynrPtRXX0Xj-6bcZ7H2QEAu?usp=sharing)
