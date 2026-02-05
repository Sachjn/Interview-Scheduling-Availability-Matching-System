# Interview Scheduling & Availability Matching System

A backend-focused SDE project that automatically matches candidate and interviewer availability.

## Tech Stack
- Backend: Python (Flask)
- Database: MySQL
- Frontend: React

## Key Features
- Availability submission
- Automatic slot matching
- Conflict-free scheduling logic

This project emphasizes algorithmic thinking and backend system design.
🗓️ Interview Scheduling & Availability Matching System
📌 Project Overview

The Interview Scheduling & Availability Matching System is a backend-driven web application designed to automate interview scheduling by matching candidate and interviewer availability. The system reduces manual coordination, avoids scheduling conflicts, and improves hiring efficiency.

This project emphasizes backend logic, algorithmic thinking, and system design, making it well-suited for Software Development Engineer (SDE) roles.

🎯 Problem Statement

In many organizations, interview scheduling is handled manually through emails or spreadsheets, which leads to:

Scheduling conflicts

Time-consuming coordination

Human errors and delays

This system solves the problem by providing an automated, rule-based scheduling mechanism.

🛠️ Tech Stack

Backend: Python (Flask)

Database: MySQL

Frontend: React (modular / extensible)

Tools: REST APIs, SQL, Git

✨ Key Features

Availability Management: Candidates and interviewers can submit available time slots.

Automatic Slot Matching: Backend logic matches common availability between candidates and interviewers.

Conflict-Free Scheduling: Ensures one interviewer is not double-booked.

Scalable Architecture: Business logic separated into service layers for easy enhancement.

🧠 Slot Matching Logic

The scheduling logic works by:

Collecting availability slots from candidates and interviewers

Comparing time slots to identify overlaps

Assigning interviews only when a common slot exists

Preventing conflicts by validating existing schedules

This logic is implemented in a dedicated service layer, allowing easy optimization in the future.

🗄️ Database Design

The database includes:

Users Table: Stores candidate and interviewer details

Availability Table: Stores available time slots

Interviews Table: Stores finalized interview schedules

This structure ensures efficient querying and clean data relationships.
