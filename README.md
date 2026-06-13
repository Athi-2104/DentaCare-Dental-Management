# 🦷 DentaCare — Dental Management System

A full-featured Dental Clinic Management Web Application built with **HTML, CSS, and Vanilla JavaScript**. No frameworks required — runs directly in the browser.

---

## 📁 Project Structure

```
dental-management/
├── index.html                  # Main entry point
├── README.md
├── public/
│   └── favicon.ico
├── src/
│   ├── styles/
│   │   ├── main.css            # Global styles, variables, reset
│   │   ├── sidebar.css         # Sidebar navigation styles
│   │   ├── dashboard.css       # Dashboard page styles
│   │   ├── components.css      # Reusable components (cards, badges, tables)
│   │   └── responsive.css      # Mobile responsive styles
│   ├── components/
│   │   ├── sidebar.js          # Sidebar navigation component
│   │   ├── header.js           # Top header component
│   │   ├── calendar.js         # Mini calendar widget
│   │   └── chart.js            # Revenue bar chart
│   ├── pages/
│   │   ├── dashboard.js        # Dashboard page
│   │   ├── patients.js         # Patient management page
│   │   ├── appointments.js     # Appointment management page
│   │   ├── doctors.js          # Doctor management page
│   │   ├── treatments.js       # Treatment records page
│   │   ├── billing.js          # Billing & payments page
│   │   ├── documents.js        # Document management page
│   │   ├── chat.js             # Doctor-patient chat page
│   │   ├── notifications.js    # Notifications page
│   │   ├── feedback.js         # Feedback & ratings page
│   │   └── settings.js         # Settings & security page
│   ├── utils/
│   │   ├── router.js           # Client-side page routing
│   │   ├── storage.js          # LocalStorage data helpers
│   │   └── helpers.js          # Utility functions (dates, currency, etc.)
│   └── assets/
│       └── logo.svg
```

---

## 🚀 Features

### 🧑‍⚕️ Patient Management
- Patient registration and profiles
- Medical & dental history records
- View previous treatments
- Search and filter patients

### 📅 Appointment Management
- Book, reschedule, cancel appointments
- Appointment status tracking (Confirmed / Pending / Completed / Cancelled)
- Calendar view with appointment indicators

### 👨‍⚕️ Doctor Management
- Doctor profiles with specialization and ratings
- Weekly availability schedule
- Patient-to-doctor assignment

### 💊 Treatment Management
- Full treatment timeline per patient
- Prescription management
- Upload X-rays and lab reports
- Treatment progress tracking

### 💳 Billing & Payments
- Generate invoices with GST calculation
- Payment history
- UPI / Card / Cash payment options
- Download invoice as PDF

### 📊 Dashboard & Reports
- Live stats: total patients, today's appointments, revenue
- Treatment breakdown chart
- Revenue bar chart (6 months)
- Pending bills overview

### 🔔 Notifications
- Appointment reminders
- Payment due alerts
- Follow-up overdue alerts

### 📁 Document Management
- Upload X-rays, prescriptions, lab reports
- Download documents
- Categorized file browser

### 💬 Chat
- Real-time-style patient-doctor messaging
- Conversation list
- Message timestamps

### ⭐ Feedback System
- Patient reviews and star ratings
- Per-doctor rating breakdown
- Overall clinic rating

### 🔒 Security & Settings
- Role-based access control (Admin / Doctor / Patient)
- System settings (clinic name, appointment duration)
- Email/SMS notification toggles
- Two-factor authentication support

---

## 🛠️ How to Run

### Option 1 — Open directly
```bash
# Just open index.html in your browser
open index.html
```

### Option 2 — Local server (recommended)
```bash
# Using Python
python -m http.server 3000

# Using Node.js live-server
npx live-server

# Then visit: http://localhost:3000
```

### Option 3 — VS Code
Install the **Live Server** extension, right-click `index.html` → **Open with Live Server**

---

## 🎨 Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure & markup |
| CSS3 | Styling, CSS variables, Grid, Flexbox |
| Vanilla JS (ES6+) | Logic, DOM manipulation, routing |
| Tabler Icons | Icon library (CDN) |
| Google Fonts | Typography |

> No React, No Vue, No Angular — Pure HTML/CSS/JS for simplicity and portability.

---

## 👥 Roles

| Role | Access |
|---|---|
| **Admin** | Full access — patients, billing, doctors, reports, settings |
| **Doctor** | Own schedule, assigned patients, prescriptions, chat |
| **Patient** | Own profile, appointments, treatment history, bills, chat |

---

## 🌐 Deployment

Deploy for free on:
- **GitHub Pages** — push to `gh-pages` branch
- **Netlify** — drag & drop the folder
- **Vercel** — `vercel deploy`

---

## 📸 Pages

| Page | Description |
|---|---|
| Dashboard | Overview stats, today's appointments, revenue chart |
| Patients | Patient list, search, add/edit |
| Appointments | Book, view, manage appointments |
| Doctors | Doctor profiles, schedules |
| Treatments | Treatment history, prescriptions, X-rays |
| Billing | Invoices, payment history, PDF download |
| Documents | File management — X-rays, reports |
| Chat | Doctor-patient messaging |
| Notifications | Reminders, alerts |
| Feedback | Patient reviews and ratings |
| Settings | RBAC, system config, security |

---

## 🤝 Contributing

1. Fork the repo
2. Create your branch: `git checkout -b feature/new-feature`
3. Commit changes: `git commit -m "Add new feature"`
4. Push: `git push origin feature/new-feature`
5. Open a Pull Request

---

Made with ❤️ for dental clinic management
