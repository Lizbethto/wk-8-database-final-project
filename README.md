
# StudentRecords Database

## Overview

This is a simple MySQL database called **StudentRecords**.
It is used to keep track of:

* Students
* Courses
* Enrollments (which student is taking which course).

---

## Database Structure

1. **Students Table** → Stores student info (ID, name, email).
2. **Courses Table** → Stores course info (ID, name, credits).
3. **Enrollments Table** → Links students and courses, with their grade.

---

## Relationships

* A **student** can enroll in many courses.
* A **course** can have many students.
* The **Enrollments table** connects students and courses.

---

## How to Use

1. Run the SQL script in MySQL Workbench
2. The script will:

   * Create the `StudentRecords` database.
   * Create the `Students`, `Courses`, and `Enrollments` tables.
   * Add relationships with **primary keys** and **foreign keys**.
