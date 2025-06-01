<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Framework-Based Site Wireframe</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: sans-serif;
      background-color: #f9f9f9;
      color: #333;
      margin: 30px;
    }
    h1, h2 {
      text-align: center;
    }
    .container {
      max-width: 800px;
      margin: auto;
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .section {
      margin-bottom: 40px;
    }
    img {
      display: block;
      width: 100%;
      max-width: 600px;
      margin: 10px auto;
      border: 1px solid #ccc;
    }
    p {
      max-width: 600px;
      margin: 10px auto;
      line-height: 1.5;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Design Sketch – Framework-Based Site</h1>

    <div class="section">
      <h2>1. Desktop View</h2>
      <img src="desktop-sketch.png" alt="Desktop wireframe sketch">
      <p>This wireframe shows the desktop version of my site using a CSS framework (e.g., Bootstrap). It includes a top navbar, a large hero section with a call to action, followed by content areas laid out in columns using grid/flexbox.</p>
    </div>

    <div class="section">
      <h2>2. Mobile View</h2>
      <img src="mobile-sketch.png" alt="Mobile wireframe sketch">
      <p>The mobile layout stacks content vertically, with a hamburger menu for navigation. Layouts collapse into one-column views using responsive classes from the framework (like Bootstrap’s grid).</p>
    </div>

    <div class="section">
      <h2>3. Landing Page (Optional)</h2>
      <img src="landing-page-sketch.png" alt="Landing page wireframe sketch">
      <p>This landing page is designed as a unique layout to focus on conversions. It removes traditional navigation, highlights a single product/service, and includes key benefits with a form or CTA at the center.</p>
    </div>
  </div>
</body>
</html>
