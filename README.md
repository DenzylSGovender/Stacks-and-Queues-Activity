# Coding Activity: Emergency Department Management System
---

##  Scenario

You have been asked to develop a simple **Emergency Department Management System** for a local hospital.

The emergency department receives patients throughout the day. Under normal circumstances, patients should be attended to in the **order in which they arrive**.

For example:

```text
08:01 - Patient 1001 - John
08:03 - Patient 1002 - Sarah
08:05 - Patient 1003 - Michael
08:07 - Patient 1004 - Thand


John arrived first, so John should normally be attended to first.

However, the hospital also needs to keep track of actions performed by medical staff on patient records.

For example:
1. Blood pressure updated
2. Medication added
3. Allergy information updated
4. Doctor's notes added

If the nurse makes a mistake and selects Undo, the most recent action must be reversed first.

Therefore, the system needs to manage two different types of data:

Patient Waiting List

Patients must be processed in the order in which they arrive.

Patient Action History

The most recent action must be reversed first.

Your task is to determine which data structure is appropriate for each requirement and develop the application.

Functional Requirements

Your application must provide functionality similar to the following:
========================================
   EMERGENCY DEPARTMENT SYSTEM
========================================

1. Register Patient
2. View Waiting Patients
3. Call Next Patient
4. Record Patient Action
5. View Most Recent Action
6. Undo Last Action
7. Display Statistics
0. Exit

Please select an option:
