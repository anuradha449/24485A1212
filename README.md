# Priority Inbox for Campus Notifications

## 📌 Problem Statement

Students receive a large number of campus notifications every day from different categories such as:

- Placement Updates
- Academic Announcements
- Club Activities
- Fee Reminders
- Examination Alerts

Many important notifications are missed because all notifications are treated equally.

This project implements a **Priority Inbox System** that automatically categorizes and prioritizes notifications so that students can focus on the most important messages first.

---

# 🎯 Objective

The objective of this project is to:

- Classify notifications based on urgency
- Assign priority levels
- Display notifications in sorted order
- Reduce notification overload
- Improve student productivity

---

# 🧠 Priority Logic

Notifications are categorized into three levels:

| Priority | Description |
|----------|-------------|
| HIGH | Urgent notifications requiring immediate attention |
| MEDIUM | Important but not urgent |
| LOW | General informational notifications |

### Example Rules

- Placement deadlines → HIGH
- Exam schedules → HIGH
- Fee reminders → MEDIUM
- Club events → LOW

---

# 🛠 Technologies Used

- Python 3
- Basic Data Structures
- Sorting Algorithms
- Object-Oriented Programming

---

# 📂 Project Structure

```text
logging_middleware/
│
├── priority_inbox.py
├── README.md
├── requirements.txt
├── notification_system_design.md
├── screenshots/
└── notification_app_be/
