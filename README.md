<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>College ERP – Project Overview</title>
</head>
<body>

  <h1>🎓 College ERP System</h1>
  <p>
    A modular, scalable College ERP system designed using
    clean architecture, normalized database design, and
    real-life academic workflows.
  </p>

  <hr />

  <h2>🧩 Main Modules</h2>
  <ul>
    <li><strong>Core</strong> – Person, Contact, Address, User, Role</li>
    <li><strong>Academic</strong> – Course, Subject, Semester, Enrollment</li>
    <li><strong>Faculty & Staff</strong> – Staff, TeachingAssignment</li>
    <li><strong>Timetable & Attendance</strong></li>
    <li><strong>Examination</strong> – Assessment, Internal, External</li>
    <li><strong>Results</strong> – SGPA, CGPA, Grades</li>
  </ul>

  <hr />

  <h2>📦 Package Structure</h2>
  <pre>
com.erp
 ├── common
 │   ├── audit
 │   ├── enums
 │   └── exception
 │
 ├── person
 │   ├── entity
 │   ├── repository
 │   └── service
 │
 ├── student
 │   ├── entity
 │   ├── enrollment
 │   └── guardian
 │
 ├── staff
 │   ├── entity
 │   └── teaching
 │
 ├── academic
 │   ├── master
 │   ├── timetable
 │   └── attendance
 │
 ├── exam
 │   ├── assessment
 │   └── result
 │
 └── security
     └── auth
  </pre>

  <hr />

  <h2>🔁 End-to-End Flow</h2>
  <ol>
    <li>Create <strong>Person</strong></li>
    <li>Assign <strong>Student / Staff</strong></li>
    <li>Create <strong>Enrollment</strong></li>
    <li>Map <strong>Teaching Assignment</strong></li>
    <li>Generate <strong>Timetable</strong></li>
    <li>Capture <strong>Attendance</strong></li>
    <li>Conduct <strong>Exams</strong></li>
    <li>Calculate <strong>Results</strong></li>
  </ol>

  <hr />

  <h2>⚙️ Tech Stack</h2>
  <ul>
    <li>Backend: Spring Boot, JPA, Hibernate</li>
    <li>Database: MySQL</li>
    <li>Frontend: React</li>
    <li>Security: Spring Security, JWT</li>
  </ul>

  <hr />

  <h2>✅ Design Principles</h2>
  <ul>
    <li>Fully normalized database</li>
    <li>Clear separation of master & transaction data</li>
    <li>Audit-enabled entities</li>
    <li>Scalable & maintainable architecture</li>
  </ul>

</body>
</html>

