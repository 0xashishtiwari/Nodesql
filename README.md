# MySQL User Seeder Script with Faker

This Node.js script uses [`@faker-js/faker`](https://www.npmjs.com/package/@faker-js/faker) to generate 100 fake user records and insert them into a MySQL database using the `mysql2` package.

## 📦 Features

- Generates random user data:
  - UUID
  - Username
  - Email
  - Password
- Bulk inserts all users into the `user` table of the `delta_app` database

## 🛠️ Requirements

- Node.js
- MySQL server
- A database named `delta_app`
- Table `user` with appropriate columns

## 📥 Installation

```bash
npm install @faker-js/faker mysql2
