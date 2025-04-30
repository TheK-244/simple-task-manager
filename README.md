Simple Task Manager – A SaaS App

📌 Project Overview

A beginner-friendly, cloud-ready Ruby on Rails SaaS application for managing personal or team tasks, following Agile practices like Scrum, TDD (RSpec), BDD (Cucumber), and continuous deployment (Heroku).

🚀 Features

Create, view, update, and delete tasks

Mark tasks as complete/incomplete

Track progress using Scrum board (GitHub Projects)

Automated testing with RSpec and Cucumber

Optional deployment to Heroku

🛠️ Technology Stack

Ruby on Rails 7 – Web framework

SQLite / PostgreSQL – Databases (SQLite for dev, PostgreSQL for production)

Git + GitHub – Version control & project tracking

RSpec – Test-Driven Development

Cucumber + Capybara – Behavior-Driven Development

Heroku – Cloud deployment (optional)

📦 Setup Instructions

1. Clone the Repository

git clone https://github.com/YOUR-USERNAME/simple-task-manager.git
cd simple-task-manager

2. Install Dependencies

Make sure Ruby (>=3.0) and Rails (7.x) are installed.

bundle install

3. Setup the Database

rails db:create db:migrate

4. Run the Server

rails server

Visit http://localhost:3000 in your browser.

✅ Testing Instructions

RSpec Unit Tests

bundle exec rspec

Cucumber BDD Tests

bundle exec cucumber

🧪 User Stories (GitHub Issues)

Role

Feature

Benefit

User

Create a task with title, description, and due date

Track work

User

View all tasks

See what needs to be done

User

Mark task complete/incomplete

Update status

User

Delete tasks

Remove completed/irrelevant tasks

All user stories are added as GitHub Issues and organized under the Scrum Board.

🚧 Project Management (Agile)

GitHub Issues = User stories

GitHub Projects = Scrum board

Milestone: MVP Release

Sprints managed via Issues and Pull Requests


📁 Folder Structure

Folder

Purpose

app/

Application logic and views

spec/

RSpec unit tests

features/

Cucumber BDD tests

db/

Migrations and schema
