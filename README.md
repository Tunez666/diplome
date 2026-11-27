# Honkai Star Rail Community Forum

A web forum built as a coursework project for a gaming community. It supports discussions across Honkai: Star Rail, Genshin Impact, and Zenless Zone Zero.

## Features

- User registration and authentication
- Role-based access for users, moderators, and administrators
- Categories, topics, posts, and nested replies
- Likes, dislikes, and notifications
- User reports and moderation tools
- Avatar and image uploads
- Administrative dashboard and database backup tools
- Yandex SmartCaptcha integration

## Tech stack

- Node.js
- Express
- MySQL
- EJS
- bcrypt
- express-session
- Multer
- Yandex SmartCaptcha

## Local setup

1. Install Node.js and MySQL.
2. Clone the repository and install dependencies:

   ```bash
   npm install
   ```

3. Create a database and import a local database schema/seed file if you have one. A production database dump is intentionally not included in this public repository.
4. Create a `.env` file based on `.env.example` and provide your own values.
5. Start the application:

   ```bash
   npm start
   ```

The application listens on port 8080 by default.

## Environment variables

See [\.env.example](.env.example). Never commit real credentials, API keys, session secrets, database dumps containing personal data, or production backups.

## Notes

This project was created as coursework. It is published as a demonstration of the implementation and is not presented as a production-ready service.
