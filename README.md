# README

# Re-Former

A small Rails app that builds a user sign-up and edit form two ways:
hand-written HTML and Rails' `form_with` helper.

## What it demonstrates
- Building a form with raw HTML, including CSRF tokens
- Strong parameters (`require` / `permit`)
- Model validations and displaying error messages
- Create and edit flows (POST vs PATCH)

## Tech
Ruby, Rails 7, SQLite, Turbo

## Run it locally
bundle install
rails db:migrate
rails server
Then visit http://localhost:3000/users/new

## What I learned
Short notes on what clicked, such as how Rails fakes PATCH with a hidden `_method` field.
