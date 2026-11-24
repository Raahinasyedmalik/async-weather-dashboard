# TaskFlow — JavaScript Logic & State Management To-Do Application

An interactive client-side To-Do List application demonstrating clean JavaScript state management, dynamic DOM manipulation, event delegation, and `window.localStorage` data persistence.

## Key Features
- **Full CRUD Functionality:** Create tasks with priority levels, read/render dynamically, update task titles inline or toggle completion status, and delete individual or completed tasks.
- **Automatic `window.localStorage` Persistence:** All task mutations and active filter states persist seamlessly across browser reloads.
- **Multi-State Filtering (`All`, `Active`, `Completed`):** Real-time task metrics and filter tabs.
- **Delegated Event Listeners:** Single centralized click listener attached to `ul#task-list` using `event.target.closest()`.
-