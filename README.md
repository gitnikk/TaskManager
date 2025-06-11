# TaskManager

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.2.11.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

🚀 Angular Coding Practice Task: Task Manager App
Objective:
Build a mini "Task Manager" application where users can create, view, edit, delete, and filter their tasks.

🧱 Requirements
1. Pages/Components
HomeComponent

Display a list of all tasks

Filter: Show All, Completed, Pending

TaskFormComponent

For creating/editing a task using Angular Reactive Forms

TaskDetailComponent

View full details of a single task

2. Task Model
ts
Copy
Edit
export interface Task {
  id: number;
  title: string;
  description: string;
  dueDate: string;
  isCompleted: boolean;
}
3. Features to Implement
✅ Create a new task

✅ Edit a task

✅ Delete a task

✅ Mark task as completed

✅ Filter tasks by completion status

✅ View task details using route parameter (e.g., /task/3)

✅ Form validation (title and due date are required)

🌐 Bonus Points
🧪 Write basic unit tests for a service or component

💾 Use localStorage to persist tasks

📦 Use RxJS BehaviorSubject in a service for state management

🌍 Add a simple route guard to block navigation if the form is dirty

📱 Make it mobile responsive using Angular Material or TailwindCSS

🧰 Tools/Modules You Should Use
@angular/forms (ReactiveFormsModule)

@angular/router

HttpClientModule (mock API or use local storage)

Optionally Angular Material for UI

🧠 Skill Areas Tested
Component interaction

Routing & route params

Forms & validation

Service and state management

Conditional rendering (ngIf, ngFor, etc.)

CRUD operations

Performance with change detection (OnPush if you want to go advanced)

