# SQL-Hospital-Project
Relational MySQL database for managing hospital recruitment, candidates, skills, positions and interviews.
## Overview

The database manages information relating to hospitals, candidates,
job positions, skills and interviews. It also records candidate
skills, skills required for individual positions and whether a
candidate received a job offer following an interview.

## Technologies

- SQL
- MySQL
- MySQL Workbench

## Database Structure

The database contains tables for:

- Hospitals
- Candidates
- Positions
- Skills
- Interviews
- Candidate Skills
- Position Skills

Many-to-many relationships are used to connect candidates with
their skills and positions with their required skills.

## SQL Techniques

This project demonstrates:

- Relational database design
- Primary and foreign keys
- Many-to-many relationships
- JOINs
- WHERE filtering
- Aggregate functions
- GROUP BY
- HAVING
- Stored procedures
- Parameterised queries
- Database constraints

## Functionality

Stored procedures are used to insert and query data, including:

- Searching hospitals and candidates
- Matching candidate skills with position requirements
- Finding positions requiring specific skills
- Counting successful job offers
- Searching interviews by date
- Identifying candidates who attended multiple interviews

## Documentation

The repository also contains the project report and ER diagram
describing the database structure and design decisions.
