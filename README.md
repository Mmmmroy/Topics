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

 ## Code illustration
 For model 2, we re-ran the model and adjusted the parameters, the results are both uploaded (named as detailed value).

1. **model2_V5.ipynb** is the original model.
2. **model2_imp_Capacity.ipynb** is the model only improved with capacity constraints.
3. **model2_imp_Virtual_classrooms.ipynb** is the model only improved with virtual classrooms.
4. **model2_imp_Capacity_Virtual.ipynb**  is the model combined with all aspects of optimal methods.
5. **model2_imp_problem_slover.ipynb** is the model test to find the optimal parameters.
6. **model2_analysis_plot.ipynb** is the analysis of the classroom usage by different kinds of figures.
