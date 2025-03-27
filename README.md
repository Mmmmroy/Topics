# Academic Scheduling Optimization Framework 🎓⏱️

A production-ready optimization system for university course scheduling, implementing hybrid MILP models with soft constraints and virtual resource management. Achieves **68% classroom utilization** and **zero infeasible weeks** in real-world deployment.

## Key Features
- **Two-Stage MILP Optimization**  
  ```mermaid
  graph LR
    A[Time Slot Allocation] --> B[Classroom Assignment]
    B --> C[Conflict-Free Schedule]

## Data Structure
/data realdata_final.xlsx
├── Illustrate               # Institutional rules (max exams/week, etc.)
├── ActivitiesInfo           # 211 activities (course_id, type, duration)      
├── Class_Course_Schedule    # 53 courses (id, name, type, enrollment)# Instructor time preferences
└── ClassroomsInfo           # 53 courses (id, name, type, enrollment)
