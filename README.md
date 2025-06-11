# 📝 Task Manager App (Angular)

A simple Task Manager web application built with Angular. This project is designed to help you practice core Angular concepts typically assessed in technical interviews.

---

## 🚀 Features

- ✅ Create, update, and delete tasks
- ✅ View individual task details
- ✅ Filter tasks by completion status (All / Completed / Pending)
- ✅ Mark tasks as completed
- ✅ Form validation with Angular Reactive Forms
- ✅ Route-based navigation
- ✅ LocalStorage support for persistent tasks

---

## 🧱 Components

### 1. `HomeComponent`
- Displays all tasks
- Filtering options (All, Completed, Pending)
- Buttons to edit, delete, or complete a task

### 2. `TaskFormComponent`
- Reusable for both creating and editing a task
- Built with Angular Reactive Forms
- Validations for `title` and `dueDate`

### 3. `TaskDetailComponent`
- Displays the complete information of a task using route params

---

## 📦 Data Model

```ts
export interface Task {
  id: number;
  title: string;
  description: string;
  dueDate: string;
  isCompleted: boolean;
}
```
---

## 🧠 Concepts Practiced
- ✅ Components & Lifecycle Hooks
- ✅ Routing & Route Parameters
- ✅ Reactive Forms & Form Validation
- ✅ Services & Dependency Injection
- ✅ State Management using RxJS BehaviorSubject
- ✅ LocalStorage for data persistence
- ✅ Angular Pipes & Directives (*ngIf, *ngFor, etc.)
- ✅ Modular Architecture

----

## 🌐 Bonus Features (Optional)
- 🧪 Unit tests for services or components
- 🧠 Dirty form guard using CanDeactivate
- 📱 Responsive design using Angular Material or TailwindCSS
- 🧩 ChangeDetectionStrategy.OnPush for performance

---

## 📁 Folder Structure (Suggested)

```ts
src/
│
├── app/
│   ├── components/
│   │   ├── home/
│   │   ├── task-form/
│   │   └── task-detail/
│   ├── services/
│   ├── models/
│   ├── guards/
│   └── app-routing.module.ts
│
├── assets/
└── environments/

```

## 🧠 Getting Started

# Clone the repo
git clone https://github.com/your-username/task-manager-angular.git

# Navigate into the project directory
cd task-manager-angular

# Install dependencies
npm install

# Run the development server
ng serve



---

## 🙋‍♂️ Maintained By
Nikhil — aspiring Project Manager, Software Developer, and future entrepreneur 🚀
