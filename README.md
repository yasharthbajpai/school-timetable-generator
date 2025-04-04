# Programming Assignment: School Timetable Generator

## Assignment Description

In this assignment, you will implement a solution for generating an optimal weekly timetable for a school. The program should create a schedule based on classes, subjects, teachers, and period requirements while satisfying various constraints.

## Problem Statement

A school needs an automated way to create their weekly timetable. They have several classes of students, a set of subjects that need to be taught, and teachers who are qualified to teach specific subjects. The goal is to create a valid timetable that satisfies all the requirements and constraints.

### Input Constraints

1. Each class needs to study a specific set of subjects.
2. Each subject requires a specific number of periods per week for each class.
3. Each teacher can only teach specific subjects (based on their qualifications).
4. Teachers cannot teach more than one class simultaneously.
5. Each day consists of exactly 6 periods, 5 days per week (Monday through Friday).
6. Each period is 1 hour long.
7. All classes must have all their required periods scheduled within the week.

### Expected Output

The program should generate a complete timetable for all classes that satisfies all constraints, showing:
- Which teacher teaches which subject to which class during each period
- A clear visualization of the weekly schedule for each class and teacher

## Getting Started

This assignment has no external dependencies and requires only Python 3.6 or higher.

1. Fork the repository
2. Open the repository in GitHub Codespaces
3. No additional setup is required - you can start coding immediately
4. To run the program: `python main.py`

## Implementation Instructions

### Required Functions

1. `generate_timetable()`: Create a valid timetable meeting all constraints
2. `display_timetable()`: Show the timetable in a readable format
3. `validate_timetable()`: Verify the timetable satisfies all constraints

### Data Structure

The provided `main.py` file contains the input data structure:
- Classes (e.g., "Class 6A", "Class 6B", etc.)
- Subjects (Mathematics, Science, English, etc.)
- Teachers and their teaching capabilities
- Period requirements for each class and subject

Do not modify these input data structures.

### Validation Requirements

Your solution must check that:
- All classes get the required number of periods for each subject
- Teachers only teach subjects they're qualified for
- No teacher is scheduled to teach two classes at the same time

### Output Format

Your timetable display should be clear and organized, showing:
- Day and period information
- Subject and teacher for each class during each period

## Testing Your Solution

To test your implementation:

1. Run the program: `python main.py`
2. The program will:
   - Generate a timetable
   - Validate the timetable
   - Display the timetable (if valid)

If successful, you should see a complete timetable that satisfies all constraints.

## Evaluation Criteria

Your solution will be evaluated based on:
1. **Correctness**: Does the generated timetable satisfy all constraints?
2. **Completeness**: Are all required periods scheduled for all classes?
3. **Code quality**: Is the code well-structured, commented, and readable?
4. **Output clarity**: Is the timetable presented in a clear, understandable format?

## Submission Guidelines

1. Submit your solution by pushing your changes to the forked repository in GitHub Codespaces
2. Include comments explaining your implementation details
3. Make sure your code runs without errors and produces valid timetables
4. Do not modify the provided input data structure
