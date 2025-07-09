#  Django Dynamic Feedback System

This project is a dynamic feedback system built using Django, where admins can create various types of questions (Text, Paragraph, Radio, Checkbox), and users can submit responses accordingly. It mimics the flexibility of Google Forms with structured backend logic.

##  Features

- Create dynamic questions with multiple input types:
  - Text
  - Paragraph (BigText)
  - Radio Buttons
  - Checkboxes
- Associate options with each question
- Store customer feedback and their responses
- Admin interface to manage questions, options, feedback, and responses
- Extendable structure for user-specific feedback or form submission history

## 🛠 Tech Stack

- **Backend:** Django 4.x
- **Database:** SQLite
- **Admin Interface:** Django Admin


![image](https://github.com/user-attachments/assets/9285ca1a-1eed-4577-90ce-87f65fcab13f)


##  Project Structure

```
feedback_project/
│
├── feedback/                # Django app
│   ├── models.py            # Models for Questions, Options, Feedback, and Responses
│   ├── admin.py             # Admin customizations
│   ├── views.py             # (To be implemented for frontend/API)
│   └── ...
│
├── db.sqlite3               # Default database
├── manage.py
└── README.md
