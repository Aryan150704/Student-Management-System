# Student-Management-System<br>
com.student.management<br>
 │<br>
├── controller<br>
├── service<br>
├── repository<br>
├── model<br>
├── dto<br>
└── config<br>

## 🏗️ Project Architecture

```text
 Browser
    │
    ▼
┌──────────────┐
│ Controller   │
└─────┬────────┘
      │
      ▼
┌──────────────┐
│   Service    │
└─────┬────────┘
      │
      ▼
┌──────────────┐
│ Repository   │
└─────┬────────┘
      │
      ▼
┌──────────────┐
│  Database    │
└──────────────┘

Controller ↔ Service ↔ Repository ↔ Database

      │
      ▼
┌────────────────────────┐
│ View (Thymeleaf UI)    │
└────────────────────────┘
```
