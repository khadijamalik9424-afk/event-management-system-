# event-management-system-
web development project  (backend &amp; frontend are both deployed)
# Event Management System

A full-stack Event Management System built with a **NestJS** backend and a **Next.js** frontend, featuring dedicated modules for managing weddings, event details, and user workflows.

🌟** System Features**
🔐 User Authentication & Roles: Secure login and registration system with role-based access (e.g., Admin, Event Planner, or Client) to control permissions.

💒 Wedding & Event Management:

Create, update, view, and delete wedding profiles or event details.

Manage event dates, timelines, venues, and descriptions easily.

👥 Guest List & RSVP Tracking:

Add and categorize guests (Family, Friends, VIPs).

Track RSVP statuses (Confirmed, Pending, Declined) and manage headcounts.

💰 Budget & Expense Tracker:

Set total event budgets and track individual expenses (decor, venue, catering, etc.).

Monitor remaining balances and payments in real-time.

📸 Vendor & Service Management:

Manage third-party vendors like photographers, caterers, decorators, and DJs.

Store vendor contact details, contracts, and payment terms.

📊 Interactive Dashboard:

A modern, responsive dashboard providing a quick overview of upcoming events, total guests, and financial summaries.

⚡ RESTful APIs & Scalability:

Robust backend built with NestJS supporting structured DTOs, controllers, and database integration.

🎨 Modern UI/UX:

Clean, fast, and responsive user interface built using Next.js and styled with Tailwind CSS for seamless mobile and desktop usage.
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
