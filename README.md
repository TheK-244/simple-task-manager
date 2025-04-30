# Simple Task Manager – A SaaS App

## 📌 Project Overview
A beginner-friendly, cloud-ready Ruby on Rails SaaS application for managing personal or team tasks, following Agile practices like Scrum, TDD (RSpec), BDD (Cucumber), and continuous deployment (Heroku).

---

## 🚀 Features
- Create, view, update, and delete tasks
- Mark tasks as complete/incomplete
- Track progress using Scrum board (GitHub Projects)
- Automated testing with RSpec and Cucumber
- Optional deployment to Heroku

---

## 🛠️ Technology Stack
- **Ruby on Rails 7** – Web framework
- **SQLite / PostgreSQL** – Databases (SQLite for dev, PostgreSQL for production)
- **Git + GitHub** – Version control & project tracking
- **RSpec** – Test-Driven Development
- **Cucumber + Capybara** – Behavior-Driven Development
- **Heroku** – Cloud deployment (optional)

---

## 📦 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR-USERNAME/simple-task-manager.git
cd simple-task-manager
```

### 2. Install Dependencies
Make sure Ruby (>=3.0) and Rails (7.x) are installed.
```bash
bundle install
```

### 3. Setup the Database
```bash
rails db:create db:migrate
```

### 4. Run the Server
```bash
rails server
```
Visit `http://localhost:3000` in your browser.

---

## ✅ Testing Instructions

### RSpec Unit Tests
```bash
bundle exec rspec
```

### Cucumber BDD Tests
```bash
bundle exec cucumber
```

---

## 🧪 User Stories (GitHub Issues)
| Role | Feature | Benefit |
|------|---------|---------|
| User | Create a task with title, description, and due date | Track work |
| User | View all tasks | See what needs to be done |
| User | Mark task complete/incomplete | Update status |
| User | Delete tasks | Remove completed/irrelevant tasks |

All user stories are added as [GitHub Issues](https://github.com/YOUR-USERNAME/simple-task-manager/issues) and organized under the **Scrum Board**.

---

## 🚧 Project Management (Agile)
- GitHub Issues = User stories
- GitHub Projects = Scrum board
- Milestone: `MVP Release`
- Sprints managed via Issues and Pull Requests

---

## 📁 Folder Structure
| Folder | Purpose |
|--------|---------|
| `app/` | Application logic and views |
| `spec/` | RSpec unit tests |
| `features/` | Cucumber BDD tests |
| `db/` | Migrations and schema |

---

## 🔖 Final Checklist
- [x] All features implemented (CRUD, complete/incomplete, delete)
- [x] RSpec unit tests created and passing
- [x] Cucumber scenarios written and passing
- [x] GitHub Issues tracked and resolved
- [x] README written
- [ ] (Optional) Deployed to Heroku

---

## 📎 Submission
Submit your GitHub repository link (and optional Heroku app URL).

🎉 **Congratulations!** You’ve created a full-featured, tested, and optionally deployed Rails SaaS Task Manager from scratch.
