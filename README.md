# Learning Management System

A web application for organising lessons into courses and managing the classrooms where those courses are taught. Our five-person team built it over nine weeks using Agile Scrum at Monash University Malaysia.

## My contribution

I helped design the [PostgreSQL database schema](backend/models/schema.sql) for the LMS. I also manually tested the application through GitLab to check that its features worked as expected.

## What the application does

- Instructors can create and edit lessons, organise them into courses, and manage classrooms.
- Students have dedicated views for their classrooms, courses, and lessons.
- The application includes classroom grades and reporting views.

## Explore the code

The [React frontend](frontend/src/pages) contains the instructor and student screens. The application sends requests to the [Express routes](backend/routes) running on Node.js. The [backend models](backend/models) contain the database queries used to retrieve and update records in PostgreSQL.
