# -SmartBudgetManagger-
A project for managing Budget.
ÉCOLE SUPÉRIEURE EN INFORMATIQUE (8 MAI 1945 -
SIDI BEL ABBÈS) Department of Computer Science — 2nd
Year CPI (Academic Year 2026/2027)

ESI SBA
Soft Skills / IT

STUDENT ATTENDANCE MANAGEMENT SYSTEM

(SAMS) Mini Project Proposal — TD/TP N°2
Student Name: chaibeddera abdelkarim Course: Soft Skills & Humanities / IT Section /
Group: Section 2 / Group 11 Instructor: Dr. Salima MEFTAHE Email:
a.chaibeddera@esi-sba.dz Submission Date: November 2026

TABLE OF CONTENTS
1. Project Title Page 1 8. Development Methodology Page 2 2. Executive Summary Page 1 9. Resources & Budget Page 3 3.
Problem Statement Page 1 10. Work Plan & Timetable Page 3 4. Project Objectives Page 1 11. Risks & Mitigation Page 3 5.
Target Users & Stakeholders Page 2 12. Deliverables & Outcomes Page 3 6. Project Scope Page 2 13. Evaluation Criteria
Page 3 7. Requirements Matrix Page 2 SAMS Project Documentation
1. PROJECT TITLE
Student Attendance Management System (SAMS) — An automated web-based platform designed to
streamline student presence tracking and administrative reporting at ESI-SBA.
2. EXECUTIVE SUMMARY
The Student Attendance Management System (SAMS) is a centralized web platform designed for ESI-SBA to
automate student attendance tracking. It eliminates manual paper recording, accelerates the attendance
logging process during lectures, and provides administrators with automated, accurate absence reports in real
time.
3. PROBLEM STATEMENT
Currently, student attendance at ESI-SBA is recorded manually on paper sheets. This manual process
wastes valuable lecture time, requires significant administrative effort to compile records, and frequently
leads to human data entry errors when calculating student absence rates.
4. PROJECT OBJECTIVES
Reduce Data Entry Errors: Eliminate human mistakes caused by manual paper logging and manual tallying.
Generate Automated Absence Reports: Instantly produce structured, error-free attendance reports for
administration.
Accelerate Attendance Recording: Streamline and speed up the daily attendance logging process during
lectures.
Student Attendance Management System (SAMS) — Mini Project Proposal Page 1 of 3 5. TARGET USERS AND

STAKEHOLDERS

Teachers
Record digital attendance
rapidly during lectures and track
course-specific presence.

6. PROJECT SCOPE
Students
Access personal attendance
dashboards to monitor absence

counts in real time.
Administrators
Oversee institution-wide data
and generate automated official
absence reports.

In-Scope Features: Digital attendance logging, administrative report generation dashboard, and
role-based secure user authentication (Teachers, Students, Administrators).
Excluded Features (Excluded from Version 1.0):
SMS Automated Notifications: Excluded due to strict project budget constraints.
Biometric / Facial Recognition: Excluded due to the tight 6-week development
timeframe. 7. FUNCTIONAL AND NON-FUNCTIONAL
REQUIREMENTS
The following numbered matrix details the primary functional and non-functional requirements for SAMS:
Req ID Category Requirement Description
FR-01 Functional The system shall record and store attendance status
(Present/Absent/Excused) for each student per session.
FR-02 Functional The system shall automatically generate summary absence reports

for administrative review.

FR-03 Functional The system shall provide secure authentication for teachers, students,

and administrators.

NFR-01 Non-Func. Performance: The system must deliver fast response times (under 2 seconds

per request).

NFR-02 Non-Func. Reliability: The system must ensure zero data loss and maintain high

system availability.

8. PROPOSED METHODOLOGY AND MAIN DEVELOPMENT PHASES
The project follows a structured Agile framework divided into five sequential development phases:
1 Initiation & Requirements Gathering: Define project charter, gather user stories, and refine scope. 2
System Design: Architect database schema, design UI/UX wireframes, and establish API specs. 3

Core Development: Build frontend interfaces and backend attendance processing engines. 4 System
Testing: Perform functional unit tests, integration tests, and security evaluations. 5 Deployment &
Delivery: Deploy to web server, deliver documentation, and conduct user training.

Student Attendance Management System (SAMS) — Mini Project Proposal Page 2 of 3

9. HUMAN AND TECHNICAL RESOURCES & ESTIMATED BUDGET
Human Resources: A dedicated development team consisting of 4 to 6 full-stack software engineering
students.
Technical Resources: Web application hosting server, PostgreSQL database server, and student
development workstations.
Estimated Budget Constraint: 500,000 DA allocated for infrastructure, domain hosting, and operational testing.
10. WORK PLAN AND TIMETABLE
The project execution spans a strict 6-week development cycle as outlined below:
Timeline Phase Name Key Development Activities
Week 1 Initiation Brainstorming, idea definition, and stakeholder requirements analysis.
Week 2 Design Database modeling, system architecture design, and UI mockups.
Weeks 3–4 Development Frontend UI implementation, backend REST API development,

and integration.

Week 5 Testing System testing, bug fixing, performance optimization, and

security audit.

Week 6 Deployment Final server deployment, project documentation completion,

and presentation.

11. POTENTIAL RISKS AND MITIGATION MEASURES
Identified Risk Risk Type Mitigation Strategy
Server Crash During Demo Technical Maintain automated daily database backups and prepare a

local offline fallback server.

Data Leakage / Breach Security Implement role-based access control (RBAC) and encrypted

data communication channels.

Hardware / Sensor Delays Operational Provide standard software-based manual input fallback interfaces

for attendance.

12. DELIVERABLES AND EXPECTED OUTCOMES
Project Deliverables (Tangible Outputs): Fully functional system source code, configured relational
database, and complete technical and user documentation.

Expected Outcomes (Project Impact): Significant reduction in wasted lecture time and accelerated
administrative attendance processing.
13. MONITORING AND EVALUATION CRITERIA
Security Benchmark: Achieving zero critical vulnerabilities during security and code evaluation. System
Adoption Rate: Achieving high regular usage among ESI-SBA faculty teachers and administrative staff.

Student Attendance Management System (SAMS) — Mini Project Proposal Page 3 of 3
