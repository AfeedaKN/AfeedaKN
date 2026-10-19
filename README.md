<div align="center">

# Afeeda KN

**Full-stack developer · MERN stack · Ernakulam, Kerala**

I build web applications and care most about the systems behind the interface:
authentication, data models and clean backend structure.

[Projects](#featured-projects) · [Stack](#tech-stack) · [Current focus](#current-focus)

</div>

## About

I'm a developing full-stack engineer working mainly with React, Node.js, Express and MongoDB. My projects are learning-driven but built end to end, from login flows and role-based access to payments and admin tooling.

I enjoy the backend half of an application the most: designing the data model, protecting routes, handling edge cases like stock, refunds and expired coupons, and keeping code organised into controllers, models and middleware.

## Featured projects

### [FitVibe](https://github.com/AfeedaKN/FitVibe-Ecom): full-stack e-commerce platform

A men's shirt store with a complete shopping flow for customers and a separate admin panel.

**Stack:** Node.js · Express 5 · MongoDB/Mongoose · EJS · Passport.js · Razorpay · Cloudinary

- **Layered authentication:** email sign-up with OTP verification, Google OAuth, bcrypt password hashing and session-based access control.
- **Full order lifecycle:** cart and stock validation, three payment paths (Razorpay, wallet, Cash on Delivery), cancellations, return requests and refunds credited to a wallet.
- **Business logic beyond CRUD:** coupons with expiry, usage limits and per-user validation, plus an admin dashboard with periodic sales reports and top-selling products.
- Organised in an MVC-style structure: `controllers`, `models`, `routes`, `middlewares`, `utils`, `views`.

### [User Management System](https://github.com/AfeedaKN/user-management): MERN auth and admin app

A full-stack app where users manage their own profile and admins manage all users. *Learning project.*

**Stack:** React · Redux Toolkit · React Router · Node.js · Express · MongoDB · JWT · Multer · Cloudinary

- **JWT authentication** with protected routes, and admin routes that additionally check the user's role.
- **Image upload pipeline:** React → Express → Multer → Cloudinary → image URL stored in MongoDB.
- Admin tooling to search, create, edit and delete users, with global state managed in Redux Toolkit.

### [Netflix-inspired streaming UI](https://github.com/AfeedaKN/netflix): React frontend

A responsive streaming-style interface with sign-up and login. *Learning project.*

**Stack:** React 19 · Vite · React Router 7 · Firebase Authentication · ESLint

- Firebase Authentication flow from sign-up and login to the authenticated home page.
- Component-based UI built with hooks, reusable components and client-side routing.

## Tech stack

| Area | Used in my projects |
| --- | --- |
| **Frontend** | React, Redux Toolkit, React Router, Vite, EJS, Bootstrap, HTML, CSS, JavaScript |
| **Backend** | Node.js, Express, REST APIs, middleware, MVC structure |
| **Database** | MongoDB, Mongoose |
| **Auth and security** | JWT, bcrypt, sessions, Passport.js (Google OAuth), Firebase Auth, role-based access |
| **Integrations** | Razorpay, Cloudinary, Multer, Nodemailer |
| **Tooling** | Git, GitHub, npm, ESLint |

## Current focus

- Moving my backend work from JavaScript to **TypeScript**
- Stronger **REST API design** and validation
- **Database modelling**, including relational design with PostgreSQL
- **Data structures and algorithms** practice
- Writing more modular, maintainable code and clearer project documentation

## Get in touch

My work lives in the repositories above. Feedback on my code is welcome: feel free to open an issue on any project.
