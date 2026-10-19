<div align="center">

<img src="https://raw.githubusercontent.com/AfeedaKN/AfeedaKN/main/assets/hero.svg" alt="Afeeda KN - Developing Full-Stack Developer (MERN)" width="100%" />

<br />

[About](#about) &nbsp;•&nbsp; [Featured Projects](#featured-projects) &nbsp;•&nbsp; [How I Build](#how-i-build) &nbsp;•&nbsp; [Tech Stack](#tech-stack) &nbsp;•&nbsp; [Current Focus](#current-focus) &nbsp;•&nbsp; [Get in Touch](#get-in-touch)

</div>

---

### About

I am a developing full-stack engineer based in Ernakulam, Kerala, India, building web applications with the MERN stack (MongoDB, Express.js, React, Node.js). My focus centers on architecting secure authentication workflows, robust REST APIs, and clean data schemas for end-to-end user experiences.

Across my projects, I have implemented role-based access control, session- and token-based authentication (JWT, Passport.js Google OAuth, Firebase Auth), multi-step e-commerce checkouts with payment gateway integration (Razorpay), and image processing pipelines (Multer, Sharp, Cloudinary). I build software systematically with modular MVC patterns and predictable state management.

---

### Featured Projects

#### [FitVibe-Ecom](https://github.com/AfeedaKN/FitVibe-Ecom)
A full-featured men's shirt e-commerce web application featuring catalog management, multi-gateway transactions, and administrative controls.

`Node.js` `Express 5` `MongoDB` `Mongoose` `EJS` `Bootstrap` `Passport.js` `Razorpay` `Multer` `Cloudinary` `Sharp` `Nodemailer`

- **Checkout & Refund Architecture**: Integrated Razorpay online payments alongside Cash on Delivery and dedicated user wallet payments, complete with automatic wallet refunds upon order returns and cancellations.
- **Promotional & Coupon Engine**: Built coupon mechanics enforcing expiration timestamps, usage limits, minimum purchase amounts, and per-user redemption validation.
- **Admin Operations & Media Pipeline**: Developed an admin dashboard with sales report generation (PDF and Excel formats via PDFKit/ExcelJS), order lifecycle tracking, and an automated product image processing pipeline utilizing Multer, Sharp cropping/resizing, and Cloudinary storage.

---

#### [User Management System](https://github.com/AfeedaKN/user-management) `[Learning Project]`
A decoupled user management application featuring role-based access control, authentication state synchronization, and direct profile media uploads.

`React` `Redux Toolkit` `React Router` `Axios` `Node.js` `Express` `MongoDB` `Mongoose` `JWT` `bcrypt` `Multer` `Cloudinary`

- **Decoupled Auth & Route Guards**: Secured frontend routing using React Router route guards paired with backend JWT authentication middleware to enforce separation between standard user and admin capabilities.
- **Profile Image Cloud Pipeline**: Created an asynchronous upload flow streaming multipart user avatars from React through Express and Multer to Cloudinary, persisting optimized URLs to MongoDB user profiles.
- **Centralized State Management**: Implemented Redux Toolkit slices to manage asynchronous authentication workflows, token persistence, and instant administrative user search and updates.

---

#### [Netflix-inspired UI](https://github.com/AfeedaKN/netflix) `[Learning Project]`
A responsive media browsing and streaming interface built with React 19 and Firebase Authentication.

`React 19` `Vite` `React Router 7` `Firebase Auth` `TMDB REST API` `react-toastify` `ESLint`

- **Dynamic Catalog via TMDB REST API**: Integrated TMDB REST API endpoints (`now_playing`, `top_rated`, `popular`) to fetch categorized movie rows, dynamic backdrop imagery, and embedded trailer playback.
- **Firebase Authentication Flow**: Implemented user registration, sign-in, and persistent session management managed through Firebase Auth with notification feedback via `react-toastify`.
- **Modern React 19 Tooling**: Constructed with Vite and React Router 7 for instant module reloading, parameterized video routes (`/player/:id`), and mobile-responsive layout styling.

---

### How I Build

<div align="center">
  <img src="https://raw.githubusercontent.com/AfeedaKN/AfeedaKN/main/assets/request-flow.svg" alt="MERN Architecture Request and Response Lifecycle Flowchart" width="100%" />
</div>

Every full-stack feature follows a predictable, decoupled lifecycle:
1. **Client Layer**: React (or server-rendered EJS templates) captures user intent and dispatches HTTP requests via Axios or fetch.
2. **Routing Layer**: Express routes match incoming HTTP methods and URI paths, isolating public routes from protected endpoints.
3. **Middleware Pipeline**: Security layers verify identity (JWT signature or session cookie), validate payload schemas, and handle multipart uploads.
4. **Controller Layer**: Decoupled business logic handles transactions, coordinates third-party services (Razorpay, Cloudinary, Nodemailer), and prepares serialized responses.
5. **Data Layer**: Mongoose schemas enforce data validation, indexing, and type constraints against the MongoDB cluster.

---

### Tech Stack

<div align="center">
  <img src="https://raw.githubusercontent.com/AfeedaKN/AfeedaKN/main/assets/stack-marquee.svg" alt="Verified Technology Stack Marquee" width="100%" />
</div>

| Category | Technologies |
| :--- | :--- |
| **Frontend** | React, Redux Toolkit, React Router, Vite, EJS, Bootstrap, HTML5, CSS3, JavaScript (ES6+) |
| **Backend** | Node.js, Express (Express 5 & Express 4) |
| **Database** | MongoDB, Mongoose |
| **Auth and Security** | JWT (JSON Web Tokens), bcrypt, Passport.js (Google OAuth 2.0), Firebase Auth, express-session |
| **Integrations** | Razorpay, Cloudinary, Multer, Sharp, Nodemailer, PDFKit, ExcelJS |
| **Tooling** | Git, GitHub, npm, Postman, ESLint |

---

### Current Focus

- **TypeScript Backend Development**: Adding static types to Express controllers, middleware pipelines, and API payloads for early error detection.
- **REST API Design and Validation**: Designing consistent RESTful status codes, structured JSON error formats, and schema-driven input validation.
- **Database Modelling with PostgreSQL**: Learning relational data modeling, table normalization, foreign keys, and SQL querying.
- **Data Structures and Algorithms (DSA)**: Strengthening problem-solving fundamentals across arrays, strings, linked lists, trees, and algorithmic complexity.
- **Cleaner Documentation**: Writing comprehensive API documentation, architecture overviews, and reproducible environment templates.

---

### Get in Touch

I welcome technical discussions, code reviews, and feedback. Feel free to open an issue or start a discussion on any of my [repositories](https://github.com/AfeedaKN?tab=repositories).

---

<p align="center">
  <img src="https://raw.githubusercontent.com/AfeedaKN/AfeedaKN/main/assets/footer-wave.svg" alt="" width="100%" />
</p>
