<div align="center">

<img src="https://raw.githubusercontent.com/AfeedaKN/AfeedaKN/main/assets/hero.svg" alt="Afeeda KN, full-stack developer. React, Node.js, TypeScript, PostgreSQL, MongoDB." width="100%">

<br>

**[About](#about)** &nbsp;•&nbsp; **[Featured Projects](#featured-projects)** &nbsp;•&nbsp; **[How I Build](#how-i-build)** &nbsp;•&nbsp; **[Tech Stack](#tech-stack)** &nbsp;•&nbsp; **[Current Focus](#current-focus)** &nbsp;•&nbsp; **[Get in Touch](#get-in-touch)**

</div>

---

<a id="about"></a>
## 👋 About

I'm a full-stack engineer based in Ernakulam, Kerala, India, building modern web applications with **TypeScript, JavaScript, React, Node.js, Express, PostgreSQL, and MongoDB**. My projects are built end to end, from login flows and role-based access control to payment integrations and admin tooling.

I enjoy the backend half of an application the most: architecting reliable data models in PostgreSQL and MongoDB, securing routes, and handling the real-world edge cases that make an app robust—like stock validation, wallet refunds, and coupon redemption rules.

---

<a id="featured-projects"></a>
## 🚀 Featured projects

### [FitVibe](https://github.com/AfeedaKN/FitVibe-Ecom) · full-stack e-commerce platform

A men's shirt store with a complete shopping flow for customers and a separate admin panel.

`Node.js` `Express 5` `MongoDB` `Mongoose` `EJS` `Bootstrap` `Passport.js` `Razorpay` `Multer` `Cloudinary` `Sharp` `Nodemailer`

- **Layered authentication:** OTP-verified sign-up, Google OAuth, bcrypt hashing and session-based access control.
- **Full order lifecycle:** cart and stock validation, three payment paths (Razorpay, wallet, Cash on Delivery), cancellations, returns and refunds credited to a wallet.
- **Business rules beyond CRUD:** coupons with expiry, usage limits and per-user validation, plus an admin dashboard with periodic sales reports.
- **Structured MVC-style:** `controllers`, `models`, `routes`, `middlewares`, `utils`, `views`.

---

### [User Management System](https://github.com/AfeedaKN/user-management) · MERN auth and admin app

Users manage their own profile and admins manage everyone else. *Learning project.*

`React` `Redux Toolkit` `React Router` `Axios` `Node.js` `Express` `MongoDB` `Mongoose` `JWT` `bcrypt` `Multer` `Cloudinary`

- **JWT authentication** with protected routes, and admin routes that also check the user's role.
- **Image upload pipeline:** React → Express → Multer → Cloudinary → image URL saved in MongoDB.
- **Admin tooling:** search, create, edit and delete users, with predictable global state managed via Redux Toolkit.

---

### [Netflix-inspired streaming UI](https://github.com/AfeedaKN/netflix) · React frontend

A responsive streaming-style interface with sign-up and login. *Learning project.*

`React 19` `Vite` `React Router 7` `Firebase Auth` `TMDB REST API` `react-toastify` `ESLint`

- **Firebase Authentication flow** from sign-up and login to the authenticated home page with toast feedback notifications.
- **Dynamic movie catalog via TMDB REST API:** fetches categorized media rows, backdrop art, and trailer video routes (`/player/:id`).
- **Component-based UI** using modern React 19 hooks, client-side routing, and responsive layouts.

---

<a id="how-i-build"></a>
## 🧭 How I build

Every backend I write follows the same path. A request is validated, authorised, acted on, persisted, and answered.

<div align="center">
  <img src="https://raw.githubusercontent.com/AfeedaKN/AfeedaKN/main/assets/request-flow.svg" alt="Animated diagram: a request travels from a React client through an Express route, auth middleware and controller to MongoDB, then a 200 OK response returns." width="100%">
</div>

---

<a id="tech-stack"></a>
## 🧰 Tech stack

<div align="center">
  <img src="https://raw.githubusercontent.com/AfeedaKN/AfeedaKN/main/assets/stack-marquee.svg" alt="Technologies used in my projects: React, TypeScript, Node.js, PostgreSQL, Express, MongoDB, Redux Toolkit, and more." width="100%">
</div>

| Area | Used in my projects |
| :--- | :--- |
| **Languages** | TypeScript, JavaScript (ES6+), SQL, HTML5, CSS3 |
| **Frontend** | React, Redux Toolkit, React Router, Vite, EJS, Bootstrap |
| **Backend** | Node.js, Express (Express 5 & Express 4), REST APIs, middleware, MVC structure |
| **Databases** | PostgreSQL, MongoDB, Mongoose |
| **Auth and security** | JWT (JSON Web Tokens), bcrypt, express-session, Passport.js (Google OAuth), Firebase Auth, role-based access |
| **Integrations** | Razorpay, Cloudinary, Multer, Sharp, Nodemailer, PDFKit, ExcelJS |
| **Tooling** | Git, GitHub, npm, Postman, ESLint |

---

<a id="current-focus"></a>
## 🎯 Current focus

- **System design & scalable backend architecture** (microservices, modular layers, event-driven patterns)
- **Performance optimization & caching** (database query tuning, indexing strategies, Redis)
- **Advanced RESTful API design** (strict schema validation, contract testing, robust error handling)
- **Data structures and algorithms** practice
- **Automated testing & CI/CD** (unit and integration testing, clean maintainable documentation)

---

<a id="get-in-touch"></a>
## 🤝 Get in touch

My work lives in the repositories above. Feedback on my code is welcome: feel free to open an issue or start a discussion on any project.

---

<p align="center">
  <img src="https://raw.githubusercontent.com/AfeedaKN/AfeedaKN/main/assets/footer-wave.svg" alt="" width="100%">
</p>
