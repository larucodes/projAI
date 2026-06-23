Step 1: Database Design (Version 1)

We'll keep it simple.

Users Table
users
-----
id
name
email
password
degree
branch
semester
cgpa
created_at

Example:

1
Laranya
laranya@gmail.com
******
B.Tech
AI & DS
6
8.4
Goals Table
goals
-----
id
user_id
goal_name
goal_type
target_date

Examples:

MS in Germany
Higher Studies

ML Engineer
Career
Skills Table
skills
------
id
skill_name
category

Examples:

Python
Programming

SQL
Database

Machine Learning
AI
User Skills Table

This tracks what the user knows.

user_skills
-----------
id
user_id
skill_id
proficiency

Example:

Laranya
Python
80
Projects Table
projects
--------
id
user_id
project_name
description
status

Status:

Planning
In Progress
Completed
Roadmaps Table
roadmaps
--------
id
user_id
month
task
status

Example:

July
Learn SQL Joins

August
Build Flask Project
Step 2: User Flow

Draw this in Excalidraw, Canva, or paper.

User Registration
       ↓
Profile Setup
       ↓
Goal Selection
       ↓
Skill Assessment
       ↓
Readiness Score
       ↓
Gap Analysis
       ↓
Roadmap Generation
       ↓
Dashboard
Step 3: Dashboard Features

Imagine the homepage.

Welcome Section
Hello Laranya 👋
Readiness Score
MS Germany Readiness

72/100
Skills Overview
Python       ████████ 80%

SQL          ██████ 60%

ML           ███ 30%
Current Goals
MS Germany 2027

Status:
In Progress
Recommended Next Action
Complete one Machine Learning project
Step 4: Folder Structure

Create this today.

PathPilot-AI

frontend/

backend/

database/

docs/

README.md

Inside docs:

docs/

database_schema.md

user_flow.md

project_architecture.md
Your Task Right Now (30–45 mins)

Create:

docs/database_schema.md

Paste the tables.

docs/user_flow.md

Paste the flow.

docs/project_architecture.md

Write:

Frontend:
React

Backend:
FastAPI

Database:
PostgreSQL

Authentication:
JWT

Deployment:
Vercel + Render
