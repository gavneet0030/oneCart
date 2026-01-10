<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OneCart — Online E-Commerce Web App</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
        }
        header {
            background: linear-gradient(90deg, #007bfd, #0056b3);
            color: #fff;
            padding: 40px 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            font-size: 1.2em;
            margin-top: 8px;
        }
        .container {
            padding: 40px 60px;
        }
        .section-title {
            color: #0056b3;
            font-size: 1.8em;
            margin-bottom: 15px;
            border-bottom: 3px solid #007bfd;
            display: inline-block;
        }
        .feature-box {
            background: #f7f9fc;
            border-left: 5px solid #007bfd;
            padding: 20px;
            margin: 20px 0;
        }
        .code-block {
            background: #2d2d2d;
            color: #f8f8f2;
            padding: 15px;
            font-family: Consolas, monospace;
            border-radius: 8px;
            overflow-x: auto;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #eee;
            font-size: 0.9em;
            color: #555;
        }
    </style>
</head>
<body>

<header>
    <h1>OneCart</h1>
    <p>The Modern Online E-Commerce Web Application</p>
</header>

<div class="container">

    <section>
        <h2 class="section-title">Project Overview</h2>
        <p>
            <strong>OneCart</strong> is a full-stack online e-commerce web application built to deliver
            a complete shopping experience. It features product browsing, secure user login,
            shopping cart functionality, order placement, and admin controls — all in a
            scalable, maintainable, and modern codebase.
        </p>
    </section>

    <section>
        <h2 class="section-title">Core Features</h2>

        <div class="feature-box">
            <h3>1. Dynamic Product Catalog</h3>
            <p>
                Display products with images, prices, descriptions, and categories. Customers
                can filter, sort, and search to find what they want effortlessly.
            </p>
        </div>

        <div class="feature-box">
            <h3>2. User Authentication & Authorization</h3>
            <p>
                Users can create accounts, sign in, and manage their profiles securely. Admin
                roles allow product and order management from a secure dashboard.
            </p>
        </div>

        <div class="feature-box">
            <h3>3. Shopping Cart & Checkout</h3>
            <p>
                Add or remove items from the cart, update quantities, and proceed to checkout
                with real-time total calculation and validation.
            </p>
        </div>

        <div class="feature-box">
            <h3>4. Order Management</h3>
            <p>
                Users can view their order history, track status, and receive confirmation
                notifications. Admins can manage order statuses.
            </p>
        </div>

        <div class="feature-box">
            <h3>5. Admin Panel</h3>
            <p>
                A secured administration interface for inventory management, product
                listings, and order oversight.
            </p>
        </div>
    </section>

    <section>
        <h2 class="section-title">Technology Stack</h2>
        <ul>
            <li><strong>Frontend:</strong> JavaScript, HTML, CSS, React (or similar)</li>
            <li><strong>Backend:</strong> Node.js / Express (or equivalent)</li>
            <li><strong>Database:</strong> MongoDB / SQL</li>
            <li><strong>Authentication:</strong> JWT / OAuth</li>
            <li><strong>Hosting:</strong> Vercel / Netlify / Heroku</li>
        </ul>
    </section>

    <section>
        <h2 class="section-title">Quick Start (Development)</h2>

        <p>Clone the repository and install dependencies:</p>
        <div class="code-block">
            git clone https://github.com/gavneet0030/oneCart.git<br>
            cd oneCart<br>
            npm install
        </div>

        <p>Run front-end and back-end servers:</p>
        <div class="code-block">
            cd frontend<br>
            npm start<br><br>
            cd backend<br>
            npm run dev
        </div>
    </section>

    <section>
        <h2 class="section-title">Screenshots & User Experience</h2>
        <p>
            (*Here you can insert product and admin dashboard screenshots to visually enhance
            the presentation. Include colorful UI with cart, product grid, user account pages, etc.*)
        </p>
    </section>

    <section>
        <h2 class="section-title">Contributing & License</h2>
        <p>
            Contributions are welcome. Fork the project, create feature branches, and submit
            pull requests. Ensure code quality and documentation for review.
        </p>
    </section>

</div>

<footer>
    OneCart • Designed and Developed by Your Name • All Rights Reserved
</footer>

</body>
</html>
