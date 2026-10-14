# Employee Raise Issue – ServiceNow

## 📌 Overview

Employee Raise Issue is a custom ServiceNow application designed to provide employees with a simple and structured way to report IT and workplace issues through a centralized Requesting Portal. The application replaces informal issue reporting through emails, calls, or chats with a guided form that captures complete and consistent information. Each submitted issue is stored as a uniquely numbered record that can be managed and resolved by support agents.

## 🎯 Objectives

- Provide employees with a single place to report IT issues.
- Capture issue information in a structured format.
- Automatically generate a unique ticket number.
- Validate required information before submission.
- Provide dependent Category → Subcategory choices.
- Allow support agents to track and update issues.
- Improve consistency and efficiency in issue management.

## 🚀 Key Features

- Custom **Employee Raises Issue** table with auto-numbering.
- **Raise Employee Issue** Record Producer in the Service Catalog.
- Custom **Requesting Portal** for employees.
- Raise Ticket widget for quick issue submission.
- Services information widget.
- Category → Subcategory dependent choices.
- Mandatory Short Description validation.
- Read-only ticket Number field.
- Issue State lifecycle: **New → In Progress → Resolved → Closed**.
- Priority and Assignment Group fields for issue routing.
- Support-agent issue management and resolution.

## 🛠️ Technologies Used

- ServiceNow
- Service Portal
- Service Catalog
- Record Producer
- UI Policies
- Client Scripts
- Dictionary Dependency
- Custom Tables
- JavaScript
- HTML
- CSS
- ServiceNow Roles & ACLs

## 🔄 Application Workflow

Employee → Requesting Portal → Raise Ticket → Record Producer → Validation → Employee Raises Issue Table → Support Agent → Issue Resolution

## 📋 Issue Fields

The custom Employee Raises Issue table contains the following fields:

- Number
- Requester
- Category
- Subcategory
- Short Description
- State
- Priority
- Assignment Group

## 🔐 Validation & Data Management

The application uses UI Policies and dictionary dependencies to maintain data consistency. Short Description is mandatory when the State is New, the Number field is read-only, and Subcategory options depend on the selected Category.

Example:

- Network → VPN
- Hardware → Laptop
- Software → Server
- Access → Forgot Password

## 👥 User Roles

### Employee

Employees can access the Requesting Portal, select the Raise Ticket option, enter their issue details, and submit a request.

### Support Agent

Support agents can view submitted issues, manage assignments, update issue states, and resolve or close requests.

## 🧪 Testing

User Acceptance Testing (UAT) covers the major application features, including:

- Requesting Portal
- Raise Ticket widget
- Issue submission
- Requester selection
- Mandatory field validation
- Category → Subcategory dependency
- Support-agent issue handling

## 📊 Agile Development

The project follows Agile/Scrum practices including:

- Product Backlog
- User Stories
- Sprint Planning
- Story Points
- Sprint Velocity
- Burndown Chart

The project was planned across two 7-day sprints:

- **Sprint 1:** 01 October 2026 – 07 October 2026
- **Sprint 2:** 08 October 2026 – 14 October 2026

## 🔮 Future Enhancements

- Email notifications when issue state changes.
- Automatic assignment of issues.
- Automatic priority calculation.
- "My Issues" widget for employees.
- Issue analytics dashboard.
- Chatbot / Virtual Agent integration.
- Employee satisfaction survey.

## 📁 Project Documentation

The project includes documentation covering:

- Problem Statement
- Empathy Map
- Brainstorming & Idea Prioritization
- Customer Journey Map
- Functional & Non-Functional Requirements
- User Stories
- Data Flow
- Sprint Planning
- Velocity & Burndown Chart
- User Acceptance Testing
- UAT Execution & Report

## 👩‍💻 Developer

**Kammara Naga Kanvitha**

Computer Science Engineering Student | ServiceNow Developer

**Project:** Employee Raise Issue – Record Producer & Service Portal Integration Guide  
**Platform:** ServiceNow  
**Version:** v1.0 (MVP)  
**Date:** October 2026
