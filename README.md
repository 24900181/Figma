# Ex09 Event Registration Web Application
# Date:05.05.2025
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Saveetha Sports Event</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

// LOGIN

<!-- Page 1: Login/Register -->
<div class="page login-page">
  <img src="saveetha-logo.png" class="logo" alt="Saveetha Logo">
  <button class="btn cyan">LOGIN</button>
  <button class="btn magenta">REGISTER</button>
</div>

// EVENTS LIST

<!-- Page 2: Events List -->
<div class="page events-page">
  <img src="saveetha-logo.png" class="logo" alt="Saveetha Logo">
  <h2>SPORTS DAY EVENTS</h2>
  <ul class="event-list">
    <li>⭐ <span>volley ball</span></li>
    <li>⭐ <span>cricket</span></li>
    <li>⭐ <span>kabbadi</span></li>
    <li>⭐ <span>chess</span></li>
    <li>⭐ <span>kho-kho</span></li>
    <li>⭐ <span>4-100 relay</span></li>
  </ul>
</div>

// REGISTRATION FORM

<!-- Page 3: Registration Form -->
<div class="page form-page">
  <img src="saveetha-logo.png" class="logo" alt="Saveetha Logo">
  <form>
    <input type="text" placeholder="Full Name">
    <input type="date" placeholder="Date of Birth">
    <input type="text" placeholder="Department">
    <input type="text" placeholder="Register Number">
    <input type="tel" placeholder="Mobile Number">
    <input type="email" placeholder="Email ID">
    <input type="text" placeholder="Events to Register">
    <button type="submit" class="btn form-btn">Submit</button>
  </form>
</div>

// CONTACT ADMIN

<!-- Page 4: Thank You Page -->
<div class="page thankyou-page">
  <img src="saveetha-logo.png" class="logo" alt="Saveetha Logo">
  <h2 class="thank-you-text">thank you</h2>
  <p class="desc">we eagerly waiting for you all to<br>participate in the games and events</p>
  <div class="contact">
    <h4>CONTACT US:</h4>
    <p>Email: <a href="mailto:Saveethaengineeringcollege@gmail.com">Saveethaengineeringcollege@gmail.com</a></p>
    <p>Phone: +91 6834571200<br>+91 8148103438</p>
  </div>
</div>

</body>
</html>

```

```
// STYLE.CSS

body {
  margin: 0;
  font-family: Arial, sans-serif;
  text-align: center;
}

.page {
  display: none;
  padding: 20px;
}

.logo {
  margin-top: 20px;
  width: 120px;
}

.btn {
  display: block;
  margin: 20px auto;
  padding: 15px 30px;
  font-size: 18px;
  font-weight: bold;
  border: none;
  cursor: pointer;
  border-radius: 5px;
}

.cyan {
  background-color: cyan;
}

.magenta {
  background-color: magenta;
  color: black;
}

.login-page {
  background-color: #867ce0;
  display: block;
}

.events-page {
  background-color: #002f3c;
  color: white;
}

.event-list {
  list-style-type: none;
  padding: 0;
  font-size: 18px;
}

.event-list li {
  margin: 10px 0;
  color: yellow;
}

.event-list span {
  color: limegreen;
}

.form-page {
  background-color: #f3d1ef;
}

.form-page form {
  display: flex;
  flex-direction: column;
  gap: 10px;
  margin: 20px auto;
  width: 80%;
  max-width: 400px;
}

.form-page input {
  padding: 10px;
  font-size: 16px;
  border: 2px solid #330066;
  border-radius: 5px;
}

.form-btn {
  background-color: #330066;
  color: white;
}

.thankyou-page {
  background-color: #fffc00;
  color: #6b0071;
}

.thank-you-text {
  font-weight: bold;
}

.desc {
  color: #6b0071;
  font-weight: bold;
}

.contact h4 {
  color: #0044cc;
}

.contact a {
  color: blue;
  text-decoration: none;
}

```
# OUTPUT:

![alt text](<Screenshot 2025-05-05 210314.png>)

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
