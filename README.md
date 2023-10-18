# MSDS460 | Assignment 2: Network Models-Project Management

### Project Statement:
Our team is involved in the software development and testing of a consumer-focused recommendation system prototype. We have 8 general tasks A,B,...,H with 8 subtasks in task D.
The goal is to uncover the optimal sequence of a series of tasks by minimizing the time to complete the project. This is based on the hours required per task and the required predessesor tasks.

### Key Files
Final Submission File: Team4_Submission.py
- Pulp used for sequencing LP CPA problem
- Equal cost per hour assumed between workers ($50)
- Minimize duration of project, constraints based on predecessor tasks
- 25% added markup to project cost for final cost to client

Input Required for File: ProjectManagement_Tasks.csv
- Each of the tasks and their respective ID
- ChatGPT used to calculate best case, expected, and worst case times per task

Output of text from File: Submission_Assignment2_Output.txt
- The output generated from running the file
- Project Duration Hours (best case): 872
- Project Duration Hours (expected): 1736
- Project Duration Hours (worst case): 2600

- Project Cost to Company in Wages $ (best case): 43600
- Project Cost to Company in Wages $ (expected): 86800
- Project Cost to Company in Wages $ (worst case): 130000

- Project Cost to Client in Fee $ (best case): 54500
- Project Cost to Client in Fee $ (expected): 108500
- Project Cost to Client in Fee $ (worst case): 162500

### Team Members:
- Gabrielle Digan
- Kui Shen
- Nora Alaoui
- Masoom Desai
