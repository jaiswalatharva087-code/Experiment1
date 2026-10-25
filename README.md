🛒 Shopping Cart Web Application

A clean, modern, and responsive front-end e-commerce application built using HTML5, CSS3 (Flexbox & Grid), and JavaScript. This project demonstrates structured layout design, responsive components, and basic client-side interactions across authentication, catalog browsing, and cart management modules.

📸 Preview & Screenshots

Tip: You can replace the placeholder paths below with links or paths to actual screenshots of your running project.

Product Catalog Page

Cart Summary Page





✨ Features

📱 Fully Responsive Layout: Built with a mobile-first approach using CSS Grid and Flexbox, ensuring standard layout scaling across desktops, tablets, and mobile devices.

🛍️ Product Catalog Grid: Displays product items dynamically structured with explicit CSS Grid layout rules (repeat(auto-fill, minmax(250px, 1fr))).

🛒 Shopping Cart Display: Items list view with single-item removal styling and total price calculation block.

🔑 Authentication Interfaces: Pre-built, semantic form layouts for user registration (Register.html) and user login (Login.html).

⚡ Interactive Elements: Includes interactive buttons with smooth :hover state feedback and basic client-side JavaScript alerts on cart actions.

🛠️ Technologies Used

Technology

Purpose

HTML5

Semantic structure for web pages (<header>, <main>, <nav>, <section>)

CSS3

Layout design utilizing Flexbox, CSS Grid, media queries, and utility classes

JavaScript (ES6)

DOM selection and event listeners for interaction logic

📂 Project Structure

.
├── Index.html        # Product catalog layout & main landing page
├── Index.css         # Grid styling for product cards and hover effects
├── Cart.html         # Shopping cart layout containing items & checkout section
├── Cart.css          # Flexbox styling and media queries for cart view
├── Login.html        # User login form
├── Login.css         # Styling for the login interface
├── Register.html     # User registration form
├── Register.css      # Styling for the registration interface
├── Utils.css         # Shared structural styles (Navbar, container layout, reset)
└── images/           # Assets directory for product imagery
    ├── belt.jpg
    ├── fridge.jpg
    ├── pant.jpg
    ├── shirt.jpg
    ├── shoes.jpg
    ├── sofa.jpg
    ├── tv.jpg
    ├── washing_machine.jpg
    └── watch.jpg


🚀 Getting Started

No external dependencies or package managers (like Node.js or npm) are required to run this project.

Prerequisites

All you need is a modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).

Local Installation & Setup

Clone the repository

git clone https://github.com/your-username/shopping-cart-app.git


Navigate into the project directory

cd shopping-cart-app


Open in browser

Double-click Index.html to open it directly in your browser.

Alternatively, open the directory in VS Code and use the Live Server extension for real-time reloading.

🌐 Pages Overview

Catalog (Index.html): Interactive catalog grid where users can browse listed items and click "Add to cart".

Cart (Cart.html): Displays chosen items alongside pricing metadata, quick removal controls, and checkout trigger.

Login (Login.html): Email/Password form validation UI designed for straightforward authentication flows.

Register (Register.html): Account creation form optimized for user sign-ups.

📐 Key Design Implementations

Utility Architecture: Common layout components such as header, navigation links, and container max-widths are encapsulated within Utils.css for cross-page reusability.

Adaptive Breakpoints: Custom @media queries adjust multi-column cart product rows into vertical stacked layouts on screens smaller than 600px.

🤝 Contributing

Contributions are welcome! If you have suggestions or improvements:

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📜 License

Distributed under the MIT License. See LICENSE for more information.
