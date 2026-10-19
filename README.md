<div align="center">

<img src="https://raw.githubusercontent.com/AfeedaKN/AfeedaKN/main/assets/hero.svg" alt="Afeeda KN, full-stack developer. MERN, REST APIs, authentication, data modelling." width="100%">

<br>

**[About](#about)** &nbsp;•&nbsp; **[Featured Projects](#featured-projects)** &nbsp;•&nbsp; **[How I Build](#how-i-build)** &nbsp;•&nbsp; **[Tech Stack](#tech-stack)** &nbsp;•&nbsp; **[Current Focus](#current-focus)** &nbsp;•&nbsp; **[Get in Touch](#get-in-touch)**

</div>

---

<a id="about"></a>
## 👋 About

I'm a developing full-stack engineer based in Ernakulam, Kerala, India, working mainly with **React, Node.js, Express and MongoDB**. My projects are learning-driven but built end to end, from login flows and role-based access to payments and admin tooling.

I enjoy the backend half of an application the most: designing the data model, protecting routes, and handling the edge cases that make an app feel real, like stock checks, refunds and expired coupons.

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
  <img src="https://raw.githubusercontent.com/AfeedaKN/AfeedaKN/main/assets/stack-marquee.svg" alt="Technologies used in my projects: React, Redux Toolkit, Node.js, Express, MongoDB, JWT, Passport.js, Razorpay, Cloudinary and more." width="100%">
</div>

| Area | Used in my projects |
| :--- | :--- |
| **Frontend** | React, Redux Toolkit, React Router, Vite, EJS, Bootstrap, HTML5, CSS3, JavaScript (ES6+) |
| **Backend** | Node.js, Express (Express 5 & Express 4), REST APIs, middleware, MVC structure |
| **Database** | MongoDB, Mongoose |
| **Auth and security** | JWT (JSON Web Tokens), bcrypt, express-session, Passport.js (Google OAuth), Firebase Auth, role-based access |
| **Integrations** | Razorpay, Cloudinary, Multer, Sharp, Nodemailer, PDFKit, ExcelJS |
| **Tooling** | Git, GitHub, npm, Postman, ESLint |

---

<a id="current-focus"></a>
## 🎯 Current focus

- Moving my backend work from JavaScript to **TypeScript**
- Stronger **REST API design** and request validation
- **Database modelling**, including relational design with PostgreSQL
- **Data structures and algorithms** practice
- More modular code and clearer project documentation

---

<a id="get-in-touch"></a>
## 🤝 Get in touch

My work lives in the repositories above. Feedback on my code is welcome: feel free to open an issue or start a discussion on any project.

---

<p align="center">
  <img src="https://raw.githubusercontent.com/AfeedaKN/AfeedaKN/main/assets/footer-wave.svg" alt="" width="100%">
</p>
