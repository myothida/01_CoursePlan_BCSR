# Project Assignment: Class Scheduling Problem for Simon's Rock Students

## Background
At Simon's Rock, students must navigate specific academic requirements to ensure they stay on track for graduation. To fulfill their Associate of Arts (AA) requirements, students must earn a total of 60 credits and complete at least 2 courses (6 credits) from 4 major divisions: Arts, Language and Literature, Science, Math and Computing, and Social Studies. In addition, students must complete the Writing and Thinking Workshop, Seminar I and II, and the First Year Experience. With various course offerings and scheduling options, understanding and avoiding scheduling conflicts is essential for academic success. 

## Objective
The purpose of this project is to assist Simon's Rock students in selecting courses and scheduling their classes effectively. This project will analyze course selections and help identify potential conflicts in students’ schedules.

### Data Set
Data is collected from Simon's Rock Course Listing and Catalog. 

The first dataset includes:
- **Course Number**
- **Title**
- **Credits**
- **Day/Time/Room**
- **Instructor**
- **FY** (no prerequisites) or **WP** (requires prerequisites) designation.

The second dataset includes:
- **Course Number**
- **Prerequisites**
- **Co-requisites**
- **Semester Offered**

### Program Description
You will develop a Python program that enables students to:

**Input Courses Taken**: Students will enter the courses they have already completed.
**Input Desired Courses**: Students will enter the courses they wish to take in the upcoming semester.
**Check for Scheduling Conflicts**: The program will analyze the provided courses to identify any scheduling conflicts ("crashes") based on their class timings.
**Check for Meeting prerequisites**: If a student has not taken any courses yet, the program will appropriately notify them.
**Check AA Requirements**: The program will confirm whether the selected courses meet the AA requirements, including the total number of credits and distribution across divisions.
**Check Course Difficulty Level (Optional)**: The program will provide information about the difficulty levels of the selected courses (e.g., introductory, intermediate, advanced) and ensure that students are aware of the challenges ahead.
