# Student-Management-System<br>
com.student.management<br>
 │<br>
├── controller<br>
├── service<br>
├── repository<br>
├── model<br>
├── dto<br>
└── config<br>

+----------+        +-------------+        +-------------+        +------------------+        +-----------+
| Browser  | -----> | Controller  | <----> |  Service    | <----> | Repository (DAO) | <----> | Database  |<br>
+----------+        +-------------+        +-------------+        +------------------+        +-----------+
                         |<br>
                         v<br>
                  +----------------------+
                  |   View (Thymeleaf)   |
                  +----------------------+
