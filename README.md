# Academic Scheduling Optimization Framework 🎓⏱️

A production-ready optimization system for university course scheduling, implementing hybrid MILP models with soft constraints and virtual resource management. Achieves **68% classroom utilization** and **zero infeasible weeks** in real-world deployment.

## Key Features
- **Two-Stage MILP Optimization**  
  ```mermaid
  graph LR
    A[Time Slot Allocation] --> B[Classroom Assignment]
    B --> C[Conflict-Free Schedule]

## Data Structure 
### demo : Demo_V5.xlsx
### realdata: realdata_final.xlsx
1. **Institutional Rules**
   - Contains institutional rules like **max exams/week**, etc.

2. **ActivitiesInfo**
   - Contains information about **211 activities**.
   - Fields include:
     - `course_id`: Unique identifier for each course.
     - `type`: Type of activity.
     - `duration`: Duration of the activity.

3. **Class_Course_Schedule**
   - Contains information about **53 courses**.
   - Fields include:
     - `type`: Type of course.
     - `StudentId`: Id of students enrolled.
     - `Courses`: course list of enrollment.
     - `Classid`: Student belongs to specific class.
     - **Instructor time preferences**.

4. **ClassroomsInfo**
   - Contains information about **53 courses**.
   - Fields include:
     - `id`: Unique identifier for the classroom.
     - `Capacity`: capacity of the classroom.
     - `Is_isolated`: Type of course.
     - `Available_week`: Statues of the candidate classrooms.
     

