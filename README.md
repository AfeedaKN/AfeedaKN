<div align="center">

<img src="https://raw.githubusercontent.com/AfeedaKN/AfeedaKN/main/assets/hero.svg" alt="Afeeda KN, full-stack developer. MERN, REST APIs, authentication, data modelling." width="100%">

**[Projects](#-featured-projects)** · **[How I build](#-how-i-build)** · **[Stack](#-tech-stack)** · **[Focus](#-current-focus)**

</div>

## 👋 About

I'm a developing full-stack engineer working mainly with **React, Node.js, Express and MongoDB**. My projects are learning-driven but built end to end, from login flows and role-based access to payments and admin tooling.

I enjoy the backend half of an application the most: designing the data model, protecting routes, and handling the edge cases that make an app feel real, like stock checks, refunds and expired coupons.

## 🚀 Featured projects

### [FitVibe](https://github.com/AfeedaKN/FitVibe-Ecom) · full-stack e-commerce platform

A men's shirt store with a complete shopping flow for customers and a separate admin panel.

`Node.js` `Express 5` `MongoDB` `Mongoose` `EJS` `Passport.js` `Razorpay` `Cloudinary`

- **Layered authentication:** OTP-verified sign-up, Google OAuth, bcrypt hashing and session-based access control.
- **Full order lifecycle:** cart and stock validation, three payment paths (Razorpay, wallet, Cash on Delivery), cancellations, returns and refunds credited to a wallet.
- **Business rules beyond CRUD:** coupons with expiry, usage limits and per-user validation, plus an admin dashboard with periodic sales reports.
- Structured MVC-style: `controllers`, `models`, `routes`, `middlewares`, `utils`, `views`.

### [User Management System](https://github.com/AfeedaKN/user-management) · MERN auth and admin app

Users manage their own profile and admins manage everyone else. *Learning project.*

`React` `Redux Toolkit` `React Router` `Node.js` `Express` `MongoDB` `JWT` `Multer` `Cloudinary`

- **JWT authentication** with protected routes, and admin routes that also check the user's role.
- **Image upload pipeline:** React → Express → Multer → Cloudinary → image URL saved in MongoDB.
- Admin tooling to search, create, edit and delete users, with global state in Redux Toolkit.

### [Netflix-inspired streaming UI](https://github.com/AfeedaKN/netflix) · React frontend

A responsive streaming-style interface with sign-up and login. *Learning project.*

`React 19` `Vite` `React Router 7` `Firebase Authentication` `ESLint`

- Firebase Authentication flow from sign-up and login to the authenticated home page.
- Component-based UI using hooks, reusable components and client-side routing.

## 🧭 How I build

Every backend I write follows the same path. A request is validated, authorised, acted on, persisted, and answered.

<div align="center">
<img src="https://raw.githubusercontent.com/AfeedaKN/AfeedaKN/main/assets/request-flow.svg" alt="Animated diagram: a request travels from a React client through an Express route, auth middleware and controller to MongoDB, then a 200 OK response returns." width="100%">
</div>

## 🧰 Tech stack

<div align="center">
<img src="https://raw.githubusercontent.com/AfeedaKN/AfeedaKN/main/assets/stack-marquee.svg" alt="Technologies used in my projects: React, Redux Toolkit, Node.js, Express, MongoDB, JWT, Passport.js, Razorpay, Cloudinary and more." width="100%">
</div>

| Area | Used in my projects |
| --- | --- |
| **Frontend** | React, Redux Toolkit, React Router, Vite, EJS, Bootstrap, HTML, CSS, JavaScript |
| **Backend** | Node.js, Express, REST APIs, middleware, MVC structure |
| **Database** | MongoDB, Mongoose |
| **Auth and security** | JWT, bcrypt, sessions, Passport.js (Google OAuth), Firebase Auth, role-based access |
| **Integrations** | Razorpay, Cloudinary, Multer, Nodemailer |
| **Tooling** | Git, GitHub, npm, ESLint |

## 🎯 Current focus

- Moving my backend work from JavaScript to **TypeScript**
- Stronger **REST API design** and request validation
- **Database modelling**, including relational design with PostgreSQL
- **Data structures and algorithms** practice
- More modular code and clearer project documentation

## 🤝 Get in touch

My work lives in the repositories above. Feedback on my code is welcome: feel free to open an issue on any project.

<img src="https://raw.githubusercontent.com/AfeedaKN/AfeedaKN/main/assets/footer-wave.svg" alt="" width="100%">
