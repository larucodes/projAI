Feature 1: Readiness Engine

This becomes your first real algorithm.

Example:

User goal:

MS in Germany (AI/DS)

Requirements:

Requirement	Weight
CGPA	20
Projects	20
Skills	25
Internship	15
IELTS	10
Research	10

Total = 100

Example user:

CGPA = 8.5

Projects = 2

Skills = Python, SQL

Internship = No

IELTS = No

Research = No

Output:

Readiness Score: 54/100

Strengths:
- CGPA
- Python

Weaknesses:
- Internship
- ML Projects
- IELTS

This is something you can code without AI.

Feature 2: Gap Analysis

Instead of:

Learn Machine Learning

The system should tell the user:

Missing Skills:

1. Machine Learning
2. Statistics
3. Linear Algebra

Missing Experiences:

1. Internship
2. Major AI Project
Feature 3: Roadmap Generator

Input:

Goal:
MS Germany AI

Output:

Month 1:
Complete Python

Month 2:
Learn SQL

Month 3:
Build Project

Month 4:
Apply Internship

Start with rule-based logic.

Don't use AI yet.

What you should do TODAY

Create a file:

docs/scoring_engine.md

and define 3 goals:

Goal 1

MS Germany (AI)

Requirements:

CGPA
Projects
Internship
Skills
IELTS
Goal 2

ML Engineer

Requirements:

Python
SQL
ML
Projects
Internship
Goal 3

Software Engineer

Requirements:

DSA
Projects
Git
Internship

For each goal assign weights that add to 100.

Then

Create:

docs/roadmap_rules.md

Example:

IF
Python < 50

THEN
Recommend Python Fundamentals
IF
Projects < 2

THEN
Recommend Portfolio Project
IF
Internship = No

THEN
Recommend Internship Search
