# Help Session Activity Management System

## Introduction
This project is a backend data model and ERD design for a Help Session Activity Management System aimed at organizing and optimizing academic support between students and teaching assistants (TAs). It captures scheduling, session management, TA availability, student interactions, and feedback collection.

## Motivation
Managing academic help sessions manually often leads to scheduling conflicts, missed appointments, and a lack of useful performance data. This system was developed to digitize and streamline the workflow, ensuring efficient support delivery and performance tracking in educational institutions.

## Features
- Track and manage help sessions, appointments, and ratings
- Maintain TA shift schedules and session logs
- Store student enrollment and TA-course associations
- Record real-time session attendance
- Collect feedback from students via ratings
- Provide support for multiple semesters and academic years

## System Design
The system is built around key entities:
- Student: Enrolled individuals requesting support
- TA: Teaching Assistants offering academic help
- Shift: Time slots assigned to TAs for sessions
- Session: Help interactions during TA shifts
- Appointment: One-on-one scheduled support between student and TA
- Rating: Student feedback for help sessions
- Course: Academic units linked to both students and TAs

Each entity is tightly coupled through relationships to ensure referential integrity and enable comprehensive analytics.

## Results
The ER model supports:
- Efficient scheduling and shift allocation
- Tracking student participation and feedback
- Analyzing TA performance via ratings
- Historical audit of sessions and appointments
