# Database Schema Migration

A simple Python project demonstrating database schema migration using Alembic, SQLAlchemy, and SQLite.

## Features

- Create a users table.
- Add an email column to the users table.
- Apply database migrations.
- Roll back database migrations.

## Technologies

- Python
- SQLAlchemy
- Alembic
- SQLite

## Installation

Install the required packages:

pip install -r requirements.txt

## Run migrations

Apply all migrations:

alembic upgrade head

Roll back the latest migration:

alembic downgrade -1