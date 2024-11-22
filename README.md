# Habit Tracker
#### Video Demo:
#### Description:
**Habit Tracker** is a Python-based CLI application designed to help users maintain their habits effectively. This tool provides a simple, interactive interface to add habits, track progress, and view complete tasks. Whether you're aiming to exercise daily, read weekly, or build other habits, this app supports you by keeping everything organized in one place.

---

## Features

**1. Add Habits**

Users can easily create new habits by specifying a name and frequency(e.g., daily or weekly). For instance, you might add a habit like "Morning Exercise" with a daily frequency to track your fitness journey.

**2. View Habits**

The app provides a clear, tabular display of all habits, including their name, frequency, and completion dates. This helps users quickly assess their progress.

**3. Mark Habits as Complete**
   
Users can mark habits as complete for the current day. The app records the completion date automatically, ensuring an accurate log of progress. For example, after completing "Read a book" today, the program updates the completion list with today's date.

**4. Delete Habits**

If a habit is no longer relevant, users can remove it from the tracker, keeping their list tidy.

**5. User-Friendly Interface**
   
The interface uses the `tabulate` library to format output neatly, making it easy to nevigate and read.

---

# Project Structure
```plaintext
project/
|
|-- project.py
|-- test_project.py
|-- README.md
|-- requirements.txt
```

### File Details
- project.py: Implements the habit tracking features, including adding, viewing, marking and deleting habits. It uses JSON file to store and retrieve habit date persistently.

- test_project.py: Contains pytest test cases to validate the functionality of the program, ensuring reliability.

- requirements.txt: Lists external dependencies like `tabulate` and `pytest`, simplifying the setup process.


## Installation

### Install Dependencies
`pip install -r requirements.txt`


## Usage

### Run the program
Execute the program using:
`python project.py`

### Menu Options
#### Adding a Habit
- Choose the "Add Habits" option from the menu.
- Enter the habit name and frequency(e.g., daily, weekly).

#### Viewing Habits
- Choose the "View Habits" option to see a list of all your habits and their progress.

#### Marking a Habit Complete
- Choose the "Mark Habit Complete" option and enter the habit name.
- The program will automatically record the current date as a completion data.

#### Deleting a Habit
- Choose the "Delete Habit" option and enter the habit name to remove it from the list.


## Testing
To ensure the program works as intended:

### Install `pytest`
Install `pytest` is not already installed:
`pip install pytest`

### Run the test case
`pytest test_project.py`


### Sample Test Output

=========================== test session starts ============================
collected 4 items

test_habit_tracker.py ....                                           [100%]

============================ 4 passed in 0.03s =============================

---

## Design Decisions
- **JSON for Data Storage**: Chosen for its simplicity and readibility. It allows the application to store habit data persistently without requiring a database.

- **Tabulate for formatting**: This library provides clean and readable tables for CLI output, enhancing user experience.

- **Pytest for Testing**: Ensures the core functionality of application are robust and error-free.

---

## Future Improvements
- **Remainders**: Add notifications to remid user of pending habits.
- **Progress Tracking**: Include visual statistics like streaks and completion percentages.

- **Custom Frequencies**: Allow users to set custom intervals beyond daily and weekly.

---



