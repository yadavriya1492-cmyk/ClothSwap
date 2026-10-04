# ClothSwap – Clothing Exchange & Swap Marketplace

A complete internship-ready prototype for exchanging pre-loved clothes through barter.

## Features
- Login and registration with server-side API
- 12 starter clothing listings (including 10+ dresses/clothes)
- Search, category and location filters
- Item detail pages
- Add clothing listing with image upload
- Estimated swap value and location matching fields
- Swap request workflow with Pending / Accepted / Completed status
- Negotiation chat stored in the database
- User dashboard and swap history
- Admin statistics and swap management
- Responsive design for laptop and mobile
- Express + JSON database for persistent demo data

## Technology
HTML5, CSS3, JavaScript, Node.js, Express.js, JSON database. The UI is intentionally simple so it is easy to explain during an internship presentation.

## Run in VS Code
1. Extract the ZIP.
2. Open the project folder in VS Code.
3. Open Terminal in that folder.
4. Run `npm install`.
5. Run `npm start`.
6. Open `http://localhost:3000/home.html`.

Do not open the HTML files directly with Firefox when using the backend; use the localhost address above.

## Demo login
Create a new account from Register. For admin demonstration, register with an email containing `admin` (example: `admin@clothswap.com`).

## Internship explanation
The project follows a barter marketplace model: a user lists a pre-loved clothing item, another user searches for a suitable item, proposes an exchange, negotiates through chat, and the request can be accepted/completed by the admin workflow. The project demonstrates frontend, API, persistence, CRUD-style listing creation, filtering, authentication flow, image handling, and responsive UI.
