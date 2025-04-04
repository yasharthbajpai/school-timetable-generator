# School Timetable Generator

## Problem Statement

This project implements a solution for generating a weekly timetable for a school. The program creates an optimal schedule based on classes, subjects, teachers, and period requirements.

### Input Constraints:
1. Each class needs to study a specific set of subjects.
2. Each subject requires a specific number of periods per week for each class.
3. Each teacher can only teach specific subjects.
4. Teachers cannot teach more than one class simultaneously.
5. Each day consists of exactly 6 periods per day, 5 days per week (Monday through Friday).
6. Each period is 1 hour long.
7. All classes must have all their required periods scheduled within the week.

### Expected Output:
A complete timetable for all classes that satisfies all constraints, showing:
- Which teacher teaches which subject to which class during each period
- A clear visualization of the weekly schedule for each class and teacher

## Usage

```bash
python main.py
```

## Implementation Approach

The program uses a constraint-based approach to generate a valid timetable. It:
1. Checks if a valid timetable is possible with the given constraints
2. Generates a timetable that ensures each class receives the required number of periods for each subject
3. Assigns teachers to classes based on their subject expertise
4. Ensures no teacher is scheduled to teach two classes at the same time
5. Outputs the timetable in a clear, readable format
