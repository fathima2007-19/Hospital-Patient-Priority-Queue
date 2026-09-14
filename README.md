# Hospital Patient Priority Queue

## Description

This project implements a Hospital Patient Priority Queue using C. The program allows users to add patients with different priority levels and treat the patient with the highest priority first.

## Priority Levels

- Priority 1 – Emergency
- Priority 2 – Urgent
- Priority 3 – Routine

The patient with the lowest priority number is always treated first.

## Features

- Add a new patient
- Assign a priority to each patient
- Treat the next highest-priority patient
- Remove the treated patient from the queue
- Display a menu for easy interaction

## Test Case

The following patients are added:

| Patient | Priority |
|---------|----------|
| P1 | 3 |
| P2 | 1 |
| P3 | 2 |
| P4 | 1 |
| P5 | 3 |
| P6 | 2 |

### Expected Treatment Order

P2 → P4 → P3 → P6 → P1 → P5

## Emergency Patient Test

After treating 2–3 patients, a new Emergency patient with priority 1 is added. The new Emergency patient is treated before the remaining Urgent and Routine patients.

## Programming Language

C
