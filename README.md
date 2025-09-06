# 🎓 University Database Management System

This repository contains the database structure and sample implementation for a **University Database Management System**. The system is designed to manage and organize various academic and administrative data, including student details, courses, teachers, subjects, assessments, results, library book issues, training, and extracurricular activities.

---

## 📁 Contents

The database includes the following key entities:

- **Students**: Personal details, academic info, and enrollment.
- **Teachers**: Faculty data including department and qualifications.
- **Courses**: University-offered programs and their structure.
- **Subjects**: Subjects under each course and semester-wise categorization.
- **Student Activities**: Extracurricular involvement and achievements.
- **Books Issued**: Library management and student-issued books.
- **College Assessments**: Academic evaluations and performance.
- **Results**: Semester-wise academic results of students.
- **Training**: Internships, workshops, and professional training.
- **Teacher Assignments**: Subjects and courses assigned to each teacher.

---

## 🗃️ Database Schema

The database uses a relational model with tables related via foreign keys. Below are the core tables:

| Table Name             | Description |
|------------------------|-------------|
| `students`             | Stores student personal and academic details |
| `teachers`             | Contains teacher/faculty data |
| `courses`              | List of university courses/programs |
| `subjects`             | Subjects under each course |
| `student_extra_activity` | Student participation in non-academic events |
| `book_issued`          | Tracks books issued to students from library |
| `college_assessment`   | Internal assessments and evaluations |
| `results`              | Final academic results |
| `training`             | Professional training or internships |
| `teacher_subject`      | Maps teachers to the subjects they teach |



---

## 🛠️ Technologies Used

- **Database**: MySQL / PostgreSQL / SQLite (adaptable based on use case)
  
  
- **Tools**: SQL Workbench, phpMyAdmin, DBeaver, etc.

---

   cd university-database

