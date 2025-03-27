# Academic Scheduling Optimization Framework 🎓⏱️

A production-ready optimization system for university course scheduling, implementing hybrid MILP models with soft constraints and virtual resource management. Achieves **68% classroom utilization** and **zero infeasible weeks** in real-world deployment.

## Key Features
- **Two-Stage MILP Optimization**  
  ```mermaid
  graph LR
    A[Time Slot Allocation] --> B[Classroom Assignment]
    B --> C[Conflict-Free Schedule]

## Data Structure 
### demo: Demo_V5.xlsx
### realdata: realdata_final.xlsx 
Including:

1. **Institutional Rules**

2. **ActivitiesInfo**

3. **Class_Course_Schedule**
  
4. **ClassroomsInfo**

 ### Dataset used in the model
1. Similar to realdata_v5_2_new.xlsx and adjusting parameters for testing
   - realdata_v5_1_new.xlsx (compulsory modules)
   - realdata_v5_2_new.xlsx (compulsory and optional modules)
2. processed_schedule.csv
   - model 1 results , people need to import to model 2 manually.
