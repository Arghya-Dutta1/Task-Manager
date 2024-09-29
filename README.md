# Task-Manager
This is a simple console-based Task Management Application written in C++. It allows users to manage their tasks by adding, listing, and removing tasks, as well as sorting them by priority. The application also reminds users about overdue tasks.

# Features
Add a Task: Add new tasks with a description, category, priority, and due date.
List Tasks by Priority: View all tasks sorted by their priority (from lowest to highest).
Remove Task: Remove tasks based on their index.
Task Categories: Choose from predefined categories or add tasks to the "Other" category.
Overdue Task Reminders: Automatically checks and reminds users of overdue tasks based on the current date.

# Task Structure
Each task has the following properties:
Description: Short description of the task.
Category: The category to which the task belongs (e.g., Work, Personal, Study, etc.).
Priority: Task priority on a scale of 1 (highest) to 5 (lowest).
Due Date: The due date of the task in YYYY-MM-DD format.

Example

Adding a Task:

```console
Enter task description: Complete project report
Choose a category:
1. Work
2. Personal
3. Study
4. Shopping
5. Other
Enter priority (1-5): 2
Enter due date (YYYY-MM-DD): 2024-10-01
```

Listing Tasks:

```console
Task 1:
Description: Complete project report
Category: Work
Priority: 2
Due Date: 2024-10-01
---------------------------
No past due tasks.
```

Removing a Task:

```console
Enter task index to remove: 1
```

# License
This project is licensed under the MIT License - see the LICENSE file for details.
