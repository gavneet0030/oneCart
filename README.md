<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>OneCart | Project Documentation</title>
</head>

<body style="
  margin:0;
  padding:0;
  background:linear-gradient(135deg,#f5f6fa,#eef2f7);
  font-family:'Segoe UI', Arial, sans-serif;
  color:#2c3e50;
">

<!-- ================= MAIN CONTAINER ================= -->
<div style="
  max-width:1100px;
  margin:60px auto;
  background:#ffffff;
  padding:60px;
  border-radius:14px;
  box-shadow:0 25px 60px rgba(0,0,0,0.08);
  text-align:center;
">

<!-- ================= TITLE ================= -->
<h1 style="
  font-size:3.4em;
  margin-bottom:10px;
  letter-spacing:1px;
">
  🛒 OneCart
</h1>

<p style="
  font-size:1.15em;
  max-width:900px;
  margin:20px auto 35px;
  color:#34495e;
">
  OneCart is a <strong>full-stack, database-driven online e-commerce web application</strong>
  designed to simulate real-world digital shopping systems with secure authentication,
  product management, cart processing, and complete order lifecycle control.
</p>

<!-- ================= BADGES ================= -->
<div style="
  display:flex;
  flex-wrap:wrap;
  justify-content:center;
  gap:12px;
  margin-bottom:35px;
">

<span style="background:#1e3799;color:#fff;padding:9px 20px;border-radius:30px;font-size:0.85em;">
  🔧 Full-Stack Architecture
</span>

<span style="background:#38ada9;color:#fff;padding:9px 20px;border-radius:30px;font-size:0.85em;">
  🛍️ E-Commerce Platform
</span>

<span style="background:#e55039;color:#fff;padding:9px 20px;border-radius:30px;font-size:0.85em;">
  🔗 RESTful API Design
</span>

<span style="background:#6a89cc;color:#fff;padding:9px 20px;border-radius:30px;font-size:0.85em;">
  🔐 JWT Authentication
</span>

<span style="background:#079992;color:#fff;padding:9px 20px;border-radius:30px;font-size:0.85em;">
  🧑‍💼 Role-Based Access Control
</span>

<span style="background:#b71540;color:#fff;padding:9px 20px;border-radius:30px;font-size:0.85em;">
  🎓 Academic & Industry Aligned
</span>

<span style="background:#2f3640;color:#fff;padding:9px 20px;border-radius:30px;font-size:0.85em;">
  ⚙️ Scalable & Modular Design
</span>

</div>

<p style="font-size:0.95em;">
  <strong>📌 Project Category:</strong> Web Development & Software Engineering<br>
  <strong>🧩 Application Type:</strong> Client–Server Based Online Shopping System
</p>

<hr style="margin:50px 0;">

<!-- ================= PURPOSE ================= -->
<h2 style="font-size:2.4em;">🎯 Purpose</h2>

<p style="max-width:900px;margin:25px auto;">
  The primary purpose of OneCart is to design, develop, and demonstrate a complete
  online e-commerce web application that closely reflects the functionality,
  architecture, and workflow of real-world digital shopping platforms.
  The project serves as both an <strong>academic learning model</strong> and a
  <strong>practical industry-oriented solution</strong>.
</p>

<p style="max-width:900px;margin:20px auto;">
  OneCart aims to provide a structured understanding of how modern web applications
  handle user authentication, product catalog management, shopping cart operations,
  order processing, and administrative control through a secure and scalable
  client–server architecture.
</p>

<!-- Purpose Cards -->
<div style="
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
  gap:25px;
  margin-top:35px;
">

<div style="background:#f8f9fd;padding:25px;border-radius:12px;">
  <h3>📘 Educational Purpose</h3>
  <ul style="list-style-position:inside;">
    <li>Understand full-stack development using layered architecture</li>
    <li>Apply software engineering concepts in a real project</li>
    <li>Implement secure authentication and authorization</li>
    <li>Practice RESTful API and database integration</li>
  </ul>
</div>

<div style="background:#f8f9fd;padding:25px;border-radius:12px;">
  <h3>🛠️ Practical & Technical Purpose</h3>
  <ul style="list-style-position:inside;">
    <li>Build a scalable and modular e-commerce system</li>
    <li>Separate frontend, backend, and database layers</li>
    <li>Manage real-time user interaction and persistence</li>
    <li>Support role-based access for users and admins</li>
  </ul>
</div>

<div style="background:#f8f9fd;padding:25px;border-radius:12px;">
  <h3>🧩 System-Oriented Purpose</h3>
  <ul style="list-style-position:inside;">
    <li>Ensure secure data flow</li>
    <li>Maintain cart and order lifecycle consistency</li>
    <li>Enable full administrative control</li>
    <li>Simulate real-world shopping workflows</li>
  </ul>
</div>

</div>

<p style="max-width:900px;margin:35px auto;">
  Overall, OneCart is not only a functional e-commerce platform but also a
  <strong>well-documented, maintainable, and extensible system</strong> that can
  be enhanced with advanced features such as online payments, analytics,
  notifications, and cloud deployment.
</p>

<hr style="margin:60px 0;">

<!-- ================= PROJECT OVERVIEW ================= -->
<h2 style="font-size:2.4em;">📦 Project Overview</h2>

<p style="max-width:900px;margin:25px auto;">
  OneCart is a comprehensive full-stack online e-commerce web application that
  enables users to browse products, manage a shopping cart, place orders, and
  track purchase history through a secure and interactive user interface.
</p>

<p style="max-width:900px;margin:20px auto;">
  The application is divided into three major components:
  <strong>Frontend UI</strong>, <strong>Backend API Server</strong>, and
  <strong>Database Layer</strong>. These components communicate via RESTful APIs,
  ensuring clear separation of concerns and easy maintenance.
</p>

<!-- Overview Lists -->
<div style="
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
  gap:30px;
  margin-top:40px;
">

<div>
  <h3>👤 User Capabilities</h3>
  <ul style="list-style-position:inside;">
    <li>Secure account creation and login</li>
    <li>Product browsing with details</li>
    <li>Cart management</li>
    <li>Order placement & tracking</li>
    <li>Profile management</li>
  </ul>
</div>

<div>
  <h3>🧑‍💼 Admin Capabilities</h3>
  <ul style="list-style-position:inside;">
    <li>Admin authentication</li>
    <li>Product CRUD operations</li>
    <li>Inventory management</li>
    <li>Order status updates</li>
  </ul>
</div>

<div>
  <h3>🏗️ Architectural Overview</h3>
  <ul style="list-style-position:inside;">
    <li>Client–server architecture</li>
    <li>RESTful communication</li>
    <li>Role-based access</li>
    <li>Centralized database</li>
    <li>Modular & extensible design</li>
  </ul>
</div>

</div>

<hr style="margin:60px 0;">

<!-- ================= TECHNOLOGY STACK ================= -->
<h2 style="font-size:2.4em;">🧰 Technology Stack</h2>

<div style="
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
  gap:25px;
  margin-top:35px;
">

<div style="background:#f8f9fd;padding:25px;border-radius:12px;">
  <h3>🎨 Frontend</h3>
  <ul style="list-style-position:inside;">
    <li><strong>HTML5</strong></li>
    <li><strong>CSS3</strong></li>
    <li><strong>JavaScript</strong></li>
    <li><strong>React</strong></li>
  </ul>
</div>

<div style="background:#f8f9fd;padding:25px;border-radius:12px;">
  <h3>⚙️ Backend</h3>
  <ul style="list-style-position:inside;">
    <li><strong>Node.js</strong></li>
    <li><strong>Express.js</strong></li>
    <li><strong>JWT Authentication</strong></li>
  </ul>
</div>

<div style="background:#f8f9fd;padding:25px;border-radius:12px;">
  <h3>🗄️ Database & Tools</h3>
  <ul style="list-style-position:inside;">
    <li><strong>MongoDB</strong></li>
    <li><strong>Mongoose</strong></li>
    <li>Git & GitHub</li>
    <li>Postman</li>
    <li>VS Code</li>
  </ul>
</div>

</div>

</div>
</body>
</html>
