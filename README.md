# event-management-system-
web development project  (backend &amp; frontend are both deployed)
# Event Management System

A full-stack Event Management System built with a **NestJS** backend and a **Next.js** frontend, featuring dedicated modules for managing weddings, event details, and user workflows.

## 🛠️ Tech Stack

* **Backend:** [NestJS](https://nestjs.com/) (TypeScript, REST APIs, Modular Architecture)
* **Frontend:** [Next.js](https://nextjs.org/) (React, Tailwind CSS, Modern UI)

---

## 📂 Project Structure

```text
Event-Management-System-main/
├── backend/                # NestJS API Server
│   ├── src/
│   │   ├── weddings/       # Wedding management module (Entities, DTOs, Controllers, Services)
│   │   ├── app.module.ts
│   │   └── main.ts
│   └── package.json
└── frontend/               # Next.js Web Application
    ├── public/             # Static assets and images
    ├── components/         # Reusable UI components
    ├── next.config.mjs
    └── package.json
