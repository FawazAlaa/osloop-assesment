# osloop-assesment
Project is a modern productivity dashboard built with Next.js, TypeScript, React Query, and Material UI.

# InsightBoard

It is as you required productivity-focused web application built with **Next.js**, **TypeScript**, **React Query**, and **Material UI**.  
It provides task management, note-taking, and analytics features in a clean, responsive interface.

---

## 🚀 Tech Stack

- **Framework:** Next.js (App Router)
- **Language:** TypeScript
- **UI:** Material UI (MUI)
- **Server State:** React Query (TanStack Query)
- **Forms:** React Hook Form + Zod
- **Editor:** Tiptap (Rich Text / Markdown)
- **State Management:** React Query + Zustand (UI state)
- **Styling:** MUI Theme + CSS-in-JS
- **Authentication:** Mock API (JWT-like token)

---

## ✨ Features

### 🔐 Authentication
- Email & password login
- Mock authentication API
- Token-based auth handling
- Protected routes with redirects

---

### 🗂️ Tasks Module
- Full CRUD functionality
- Kanban board (Todo / In Progress / Done)
- Filter by status and priority
- Sort by creation date or priority
- Optimistic updates using React Query
- Loading, empty, and error states
- Retry support on failed requests

**Task Model**
```ts
{
  id: number;
  title: string;
  description: string;
  priority: "low" | "medium" | "high";
  status: "todo" | "in-progress" | "done";
  createdAt: string;
  updatedAt: string;
}
