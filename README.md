# Habit Tracker

A simple Python-based CLI application for tracking the habits. The application allows to:
- Add new habits.
- View existing habits.
- Mark habits as completed.
- Delete habits.

The project uses basic Python functionality with optional integration of third-party libraries like `tabulate` for better output formatting.

---

### Features

1. **Add Habits**: Add a new habit with name and frequency (daily, weekly, etc.).
2. **View Habits**: Display a list of all habits along with their details and completed dates.
3. **Mark Habits as Complete**: Mark a habit as completed for the current date.
4. **Delete Habits**: Remove a habit from the tracker.
5. **Clean CLI Interface**: Simple to use and easy to read

---

# Project Structure

habit-tracker/
│
├── habit_tracker.py          # Main application file
├── test_habit_tracker.py     # Tests for the application
├── README.md                 # Project documentation
└── requirements.txt          # Optional: List of dependencies


### Install Dependencies
pip install tabulate


### Run the program
python project.py


## Usage
### Adding a Habit
1. Run the program
2. Choose the "Add a Habit" option from the menu.
3. Enter the habit name and frequency(e.g., daily, weekly).

### Viewing Habits
1. Choose the "View Habits" option to see a list of all your habits and their progress.

### Marking a Habit Complete
1. Choose the "Mark Habit as Complete" option and enter the habit name.
2. The program will automatically record the current date as a completion date.

### Deleting a Habit
Choose the "Delete Habit" option and enter the habit name to remove it from the list.


# Testing

## Requirements
pip install pytest

## Run the program
pytest test_project.py

## Sample Test Output

=========================== test session starts ============================
collected 4 items

test_habit_tracker.py ....                                           [100%]

============================ 4 passed in 0.03s =============================




