
# 🌐 WorkPortal: Virtual Career Fair Hub

A comprehensive networking platform designed to bridge the gap between university students, recruiters, and administrators. This system streamlines the recruitment process through real-time logistics and advanced management modules.

---

## 👥 The Development Team

| Name | GitHub Profile |
| :--- | :--- |
| **Yasmin Mohamed** | [@yasmin-mohamed55](https://github.com/yasmin-mohamed55) |
| **Haidi** | [@HAIDI-A](https://github.com/HAIDI-A) |
| **Nour Ehab** | [@nour-ehab](https://github.com/nour-ehab) |
| **Noha Emad** | [@Nohaemad19](https://github.com/Nohaemad19) |
| **Jana Amin** | [@janaadarwish](https://github.com/janaadarwish) |

---

## 🏗️ System Architecture

The project is structured into four core modules to ensure scalability and clear separation of concerns:

### 1. Student Portfolio & Engagement
* **Profile Management:** Tools for building resumes and professional portfolios.
* **Fair Navigation:** Join queues, view recommended booths, and track application status.
* **Engagement:** Submit feedback and manage profile privacy settings.

### 2. Recruiter & Booth Operations
* **Booth Management:** Post interview slots, respond to chats, and manage candidate alerts.
* **Evaluation:** Rate candidates, shortlist profiles, and download resumes.
* **Operations:** Request sponsorship tiers and monitor booth-specific traffic.

### 3. Real-Time Fair Logistics
* **Queue System:** Features `WaitQueue` and `DigitalDrop` logic to handle live traffic and session reminders.
* **Live Interaction:** Managed via `ChatSession` for timed chats and real-time file sharing.
* **Monitoring:** Active management of live fair queues and session loads.

### 4. University Admin & Analytics
* **System Oversight:** Create fair schedules and manage system-wide broadcasts.
* **Data Insights:** Access the `AnalyticsDashboard` for full fair reports and traffic analytics.
* **User Management:** Oversee all user roles and manage access/disputes.

---

## 🛠️ Technical Implementation

### Shared Core Classes
To maintain a DRY (Don't Repeat Yourself) architecture, we utilize several shared components:
* `User (abstract)`: The base class for JobSeeker, Recruiter, and Admin.
* `NotificationEngine`: Centralized service for sending alerts across all modules.
* `EIUAuthentication`: Handles secure login and SSO for all user roles.
* `SystemLogManager`: Aggregates system events and logs for debugging and security.

### Key Capabilities
* **Dynamic Scheduling:** Automated interview slot selection and queue capacity tracking.
* **Real-Time Communication:** Timed chat sessions with the ability to pause/resume queues.
* **Analytics-Driven:** Comprehensive reporting for both recruiter performance and fair-wide activity.

---

## 🚦 Getting Started

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yasmin-mohamed55/WorkPortal.git](https://github.com/yasmin-mohamed55/WorkPortal.git)# job-fair-website
