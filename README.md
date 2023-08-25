# Quiz App

Welcome to the Quiz App! This is a Ruby on Rails application that serves as a backend for a quiz game. It provides an API to fetch random quiz questions.

## Features

- Retrieve a random quiz question.
- Serve static files for the frontend (if applicable).

## Getting Started

Follow these instructions to set up and run the quiz app on your local machine.

### Prerequisites

- Ruby (version x.x.x)
- Ruby on Rails (version x.x.x)
- SQLite (for development; you can use other databases in production)

### Installation

1. Clone the repository:

   ```bash
   git clone <repository_url>
   cd quiz_app
   ```

2. Install the required gems:
   bundle install
3. Create the database and run migrations:
   rails db:create
   rails db:migrate
4. (Optional) Seed the database with sample questions:
   rails db:seed

Usage

1. Start the Rails server:
   rails server
   The app will be accessible at http://localhost:3000.

2. Use API endpoints to fetch quiz questions.
   For example:
   Get a random question:
   GET http://localhost:3000/get_question
