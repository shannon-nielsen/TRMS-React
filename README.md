# TRMS-React

## Project Description

TRMS, or Tuition Reimbursement Management System is a full-stack web application that allows employees to submit requests for reimbursements for courses, events, and certifications. These requests can then be approved or rejected by the employee's direct supervisor, department head, and a benefits coordinator while the employee is able to track the status of their requests.

## Technologies Used

* React
* Redux
* JavaScript/TypeScript
* HTML/CSS
* Express.js
* AWS-SDK
* DynamoDB

## Features

List of features ready and TODOs for future development

* Users can login, view events, and view tuition reimbursement forms
* Supervisors, department heads and benefits coordinators can accept/reject tuition reimbursement requests, and request more information
* Employees can create and edit tuition reimbursement forms
* Once approved, employees can submit a numeric grade for the event they attended
* Reimbursement amounts are calculated and deducted from the employee account balance if a passing grade is achieved

To-do list:

* Time sensitivity: employees must submit request one week prior to event start, direct supervisors and department heads must respond to requests in a timely manner, otherwise request is auto-approved
* Grade/presentation upload: employees can submit other grading formats, and supervisors can approve/reject the presentation or grade
* Employees can track form status
* Unit testing

## Getting Started

1. Clone into repo:
   - `https://github.com/shannon-nielsen/TRMS-React.git`
2. Go to the server folder of the project:
   - `cd server`
3. Install all project dependencies:
   * `npm install`
4. Setup initial tables:
   - `npm run setup`
5. Start the server:
   * `npm run start`
6. Go to the client folder:
   - `cd client`
7. Install all project dependencies:
   - `npm install`
8. Start the client:
   - `npm run start`
