MealDB Full Stack Application
Overview

MealDB is a team-developed full stack web application designed using modern enterprise development practices.

The application allows users to search meals, explore recipes, and view detailed meal information through a scalable full stack architecture.

The system is developed using Java Full Stack technologies including Spring Boot, ReactJS, MySQL, REST APIs, and Git-based collaboration.

This project follows a professional development workflow with protected branches, code reviews, and structured team responsibilities.

Team Structure

Total Members: 4 Developers

Project Lead

Jaswanth Eedara

Responsibilities:

Project architecture

Task planning

Pull Request review

Merge approvals

Conflict resolution

Deployment management

Repository management

Frontend Developer

Akshaya

Responsibilities:

React UI development

Page design

API integration

Responsive layout

User experience improvements

Primary Folder:

frontend/
Backend Developer

Akanksha

Responsibilities:

Spring Boot API development

Database integration

Business logic

Security implementation

Testing APIs

Primary Folder:

backend/
Full Stack Developer

Damayanthi

Responsibilities:

Frontend + Backend integration

API testing

Bug fixing

Feature support

Performance improvements

Works in:

frontend/
backend/
Repository Structure
Mealdb
│
├── frontend
│
├── backend
│
├── database
│
└── README.md
Development Workflow

This project uses a branch-based workflow.

The main branch is protected and cannot be modified directly.

All development must be done using feature branches.

Leader Guide
Reviewing Changes
Step 1

Open repository on GitHub.

Go to:

Pull Requests
Step 2

Open the Pull Request.

Step 3

Click:

Files Changed

Check:

Code correctness

Errors

Naming

Folder placement

Formatting

Step 4

Approve Changes

Review Changes
Approve
Submit Review
Step 5

Merge Pull Request

Merge Pull Request
Confirm Merge
Leader Controls

Leader manages:

Pull Request approvals

Merge decisions

Task assignments

Branch management

Repository settings

Deployment updates

Leader ensures:

Main branch always works

No broken builds

Clean commits

Proper structure

Developer Workflow
Step 1 Clone Repository
git clone https://github.com/jaswanth457259/Mealdb.git
cd Mealdb
Step 2 Get Latest Code

Always update before working.

git checkout main
git pull origin main
Step 3 Create Branch

Frontend example:

git checkout -b frontend-search

Backend example:

git checkout -b backend-meal-api

Fullstack example:

git checkout -b fullstack-integration
Step 4 Work and Commit
git add .
git commit -m "Implemented meal search feature"
Step 5 Push Branch
git push origin branch-name
Step 6 Create Pull Request

Open repository on GitHub.

Click:

Compare & Pull Request

Add description and create Pull Request.

Leader reviews and merges.

Branch Naming Rules

Frontend:

frontend-feature

Examples:

frontend-navbar
frontend-search
frontend-details

Backend:

backend-feature

Examples:

backend-api
backend-auth
backend-database

Fullstack:

fullstack-feature

Examples:

fullstack-integration
fullstack-login
Project Architecture
Frontend

Technology:

ReactJS

JavaScript

CSS

Features:

Meal search

Meal details

Category filtering

Responsive design

Location:

frontend/
Backend

Technology:

Java

Spring Boot

Spring Security

JPA

Features:

REST APIs

Business logic

Authentication

Database connection

Location:

backend/
Database

Technology:

MySQL

Features:

User data

Favorites

History

Location:

database/
Running the Project
Backend
cd backend
mvn spring-boot:run

Backend runs at:

http://localhost:8080
Frontend
cd frontend
npm install
npm run dev

Frontend runs at:

http://localhost:5173
Development Standards
Required Rules

Do not push to main branch

Always create branches

Pull before work

Test before push

Use clear commit messages

Keep code clean

Follow folder structure

Code Standards
Commit Message Examples

Good:

Added meal search API
Fixed login validation
Improved UI layout
Connected frontend to backend

Avoid:

update
fix
done
code
Deployment Plan

The application will be deployed using cloud services.

Deployment includes:

Backend server deployment

Frontend hosting

MySQL database hosting

Technologies Used

Backend

Java

Spring Boot

REST APIs

Maven

Frontend

ReactJS

JavaScript

CSS

Database

MySQL

Tools

Git

GitHub

Postman

Project Goals

Build a production-level full stack system

Follow professional team workflow

Implement scalable architecture

Maintain clean code standards

Deploy a working cloud application
