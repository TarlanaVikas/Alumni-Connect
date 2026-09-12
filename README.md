
![Alumni Connect](https://capsule-render.vercel.app/api?type=waving\&color=0:0F172A,45:1E3A8A,100:0EA5E9\&height=210\&section=header\&text=Alumni%20Connect\&fontSize=52\&fontColor=FFFFFF\&animation=fadeIn\&fontAlignY=38)

<p align="center">
  <strong>Connect • Network • Communicate • Grow Together</strong>
</p>

<p align="center">
  A modern university alumni management platform connecting
  <br/>
  <strong>Students • Alumni • Administrators</strong>
</p>

<br/>

<p align="center">
  <img src="https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Vite-Frontend-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>
  <img src="https://img.shields.io/badge/TailwindCSS-UI-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
  <img src="https://img.shields.io/badge/Lucide-Icons-F97316?style=for-the-badge&logo=lucide&logoColor=white"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Context%20API-State%20Management-61DAFB?style=flat-square&logo=react"/>
  <img src="https://img.shields.io/badge/React%20Router-Routing-CA4245?style=flat-square&logo=reactrouter"/>
  <img src="https://img.shields.io/badge/React%20Hook%20Form-Forms-EC5990?style=flat-square"/>
  <img src="https://img.shields.io/badge/Recharts-Analytics-22C55E?style=flat-square"/>
  <img src="https://img.shields.io/badge/Axios-HTTP%20Client-5A29E4?style=flat-square"/>
</p>

---

## ◈ The Platform

**Alumni Connect** is a comprehensive university alumni management platform designed to bring together **students, alumni, and administrators** in one connected digital ecosystem.

From professional networking and messaging to events, fundraising, AI assistance, and administration, the platform provides the tools required to build and manage an active university community.

```text
                         ALUMNI CONNECT
                               │
          ┌────────────────────┼────────────────────┐
          │                    │                    │
          ▼                    ▼                    ▼
       STUDENTS              ALUMNI              ADMIN
          │                    │                    │
          └────────────────────┼────────────────────┘
                               │
              ┌────────────────┼────────────────┐
              ▼                ▼                ▼
           NETWORK          COMMUNICATE      MANAGE
              │                │                │
              └────────────────┼────────────────┘
                               ▼
                     UNIVERSITY COMMUNITY
```

---

# ✦ Platform Highlights

<table>
<tr>
<td width="50%">

### 🔐 Authentication

Secure login and registration with role-based access for students, alumni, and administrators.

</td>
<td width="50%">

### 🤖 AI Assistant

An intelligent assistant that helps users navigate the platform and access support.

</td>
</tr>

<tr>
<td>

### 👤 Professional Profiles

Create and manage profiles containing skills, experience, social links, and professional information.

</td>
<td>

### 💬 Messaging

Connect with alumni and community members through the messaging system.

</td>
</tr>

<tr>
<td>

### 📅 Events

Create, manage, discover, and register for university and alumni events.

</td>
<td>

### 💰 Donations

Create fundraising campaigns, track donations, and visualize campaign progress.

</td>
</tr>

<tr>
<td>

### 🔎 Smart Discovery

Search and filter people, events, organizations, and other platform content.

</td>
<td>

### 📊 Admin Analytics

Monitor users, events, donations, activity, and platform statistics through the admin dashboard.

</td>
</tr>
</table>

---

# 🚀 Core Features

## 01 — Authentication & User Management

* Secure login/registration system
* Role-based access control
* Alumni, Student, and Admin roles
* Profile management
* Skills and professional experience
* Social links and professional information

---

## 02 — AI Bot Assistant

* Intelligent chat interface
* Context-aware responses
* Quick action suggestions
* Platform navigation assistance
* User support

---

## 03 — Messaging System

* Real-time chat interface
* Message history
* Message search
* Online status indicators
* File sharing capabilities

---

## 04 — Events Management

* Event creation and management
* Event registration
* Calendar integration
* Event categories
* Event filtering

---

## 05 — Donations & Fundraising

* Campaign creation and management
* Donation tracking
* Progress visualization
* Receipt generation
* Fundraising management

---

## 06 — Search & Discovery

Search across the platform with advanced filtering.

```text
People
   │
Events
   │
Organizations
   │
Content
   │
   ▼
Advanced Search + Multi-Criteria Filters
   │
   ▼
Smart Suggestions
```

Features include:

* Advanced search
* Multi-criteria filtering
* Smart suggestions
* Content categorization

---

# 🛡️ Administration

Alumni Connect includes a dedicated administrative environment for managing the entire platform.

### Admin capabilities

| Area           | Capabilities                              |
| -------------- | ----------------------------------------- |
| 👥 Users       | Student & Alumni CRUD operations          |
| 🔐 Roles       | Role assignment and permissions           |
| ⚡ Bulk Actions | Bulk delete, role changes, status updates |
| 🔎 Filtering   | Advanced search and filtering             |
| 📊 Analytics   | User analytics and reporting              |
| 📅 Events      | Event management and oversight            |
| 💰 Donations   | Donation tracking and management          |

---

# 🧩 Technical Architecture

```text
┌───────────────────────────────────────────────┐
│                   USER LAYER                  │
│                                               │
│     Student       Alumni       Administrator  │
└───────────────────────┬───────────────────────┘
                        │
                        ▼
┌───────────────────────────────────────────────┐
│                 REACT FRONTEND                │
│                                               │
│  Pages • Components • Forms • Navigation      │
└───────────────────────┬───────────────────────┘
                        │
            ┌───────────┼───────────┐
            ▼           ▼           ▼
       Context API   Router DOM   Axios
            │                       │
            ▼                       ▼
       State Layer             HTTP Layer
            │                       │
            └───────────┬───────────┘
                        ▼
              Platform Services
                        │
        ┌───────────────┼────────────────┐
        ▼               ▼                ▼
     Messaging        Events          Donations
        │               │                │
        └───────────────┼────────────────┘
                        ▼
                  Admin System
```

---

# 🛠️ Technology Stack

| Technology            | Role                        |
| --------------------- | --------------------------- |
| **React 18**          | Frontend framework          |
| **Vite**              | Development & build tooling |
| **Tailwind CSS**      | Styling and responsive UI   |
| **Lucide React**      | Icon system                 |
| **React Context API** | State management            |
| **React Router DOM**  | Application routing         |
| **React Hook Form**   | Form management             |
| **React Hot Toast**   | Notifications               |
| **Recharts**          | Charts and analytics        |
| **date-fns**          | Date handling               |
| **Axios**             | HTTP client                 |

---

# 📁 Project Structure

```text
alumni-connect/
│
└── src/
    │
    ├── components/
    │   └── Layout.jsx
    │
    ├── contexts/
    │   └── AuthContext.jsx
    │
    ├── pages/
    │   ├── Login.jsx
    │   ├── Register.jsx
    │   ├── Dashboard.jsx
    │   ├── Profile.jsx
    │   ├── Messaging.jsx
    │   ├── MailInfo.jsx
    │   ├── PeopleYouMayKnow.jsx
    │   ├── Events.jsx
    │   ├── Search.jsx
    │   ├── Donations.jsx
    │   ├── AdminDashboard.jsx
    │   └── AIBot.jsx
    │
    ├── App.jsx
    ├── main.jsx
    └── index.css
```

---

# ⚡ Getting Started

## Clone

```bash
git clone <repository-url>
cd alumni-connect
```

## Install

```bash
npm install
```

## Start Development Server

```bash
npm run dev
```

## Open

```text
http://localhost:3000
```

---

# 🔑 Demo Admin Access

The platform includes demo administrator access.

```text
Email:
admin@university.edu

or

admin@email.com

Password:
Any password
```

The admin dashboard provides tools for:

* Managing students and alumni
* Assigning roles and permissions
* Performing bulk operations
* Viewing analytics and reports
* Managing events
* Tracking donations

---

# 🎨 Design System

The application follows a consistent modern design system.

### Color Language

```text
Primary     → Blue palette
Secondary   → Gray palette
```

### Typography

**Inter** is used as the primary font family for readability and consistency.

### Interface

* Reusable UI components
* Accessible interaction patterns
* Responsive layouts
* Mobile-first approach
* Professional dashboard interfaces

---

# 🧪 Available Scripts

| Command            | Description                     |
| ------------------ | ------------------------------- |
| `npm run dev`      | Start development server        |
| `npm run build`    | Build production application    |
| `npm run preview`  | Preview production build        |
| `npm run lint`     | Run ESLint                      |
| `npm run lint:fix` | Automatically fix ESLint issues |

---

# 🌍 Deployment

Build the production application:

```bash
npm run build
```

The generated `dist` folder can be deployed to:

* Vercel
* Netlify
* AWS S3
* Any static hosting service

---

# 📱 Browser Support

Alumni Connect supports modern versions of:

| Browser | Support |
| ------- | ------- |
| Chrome  | Latest  |
| Firefox | Latest  |
| Safari  | Latest  |
| Edge    | Latest  |

---

# 🤝 Contributing

Contributions are welcome.

```text
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request
```

---

# 🔮 Future Roadmap

The platform can be expanded with:

* Real-time notifications
* Mobile application
* Advanced analytics
* External service integrations
* Multi-language support
* Video conferencing integration

---

# 🆘 Support

For support and questions:

* Create an issue in the repository
* Contact the development team
* Check the project documentation

---

# 📄 License

This project is licensed under the **MIT License**.

See the `LICENSE` file for details.

---

<p align="center">

### Built to connect a university community.

**Students → Alumni → Opportunities → Community**

<br/>

⭐ If you find **Alumni Connect** useful, consider starring the repository!

</p>
