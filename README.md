## Objective
A basic admin panel that includes user registration, login, logout
functionalities, and CRUD operations on users.
## Tech Stack

**Client:** React, TailwindCSS, Redux

**Server:** Node, Express, Zod (Validation), Mongoose

**Database:** MongoDB

## Features

- User Can Register and Login
- Admin can Add new user, delete user, view all users and update details of any user
- Password Protected using Bcryt JS and Authorization using JSON Web Token

## Video Demonstration


https://github.com/user-attachments/assets/c9421520-2727-4b60-81c1-a9a5f85235a7



## Note
- When the user registers that individual is a normal user
- Admin has rights Make someone admin or not
- The all users table is just shown to admin
- An email id-admin@mail.com and password-admin is set up of testing purposes
## Installation

Clone the Repository

```bash
git clone https://github.com/RonakSurana-2001/HealTether.git
```
For Frontend
```bash
cd frontend
npm install
npm start
```

For Backend
```bash
cd Backend
npm install
node index.js
```

Environment Files in Backend
```bash
JWT_SECRET_KEY=<JWT_SECRET_TOKEN>
MONGO_URL=<MONGO_DB_LINK>
```

Start the Developement Server
```bash
npm run dev
```
## Live Site

<a href="https://heal-tether.vercel.app/">
Live site</a>  

Backend is deployed on render and database on mongodb atlas free plan so data fetching from backend takes time. So after you perform any action you have to wait.

## Authors

 [@Ronak Surana](https://www.linkedin.com/in/ronak-surana-944550205/)

