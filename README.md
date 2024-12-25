# Ex.07 Restaurant Website
## Date: 22-12-2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Casendra - Saveetha Engineering College</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
        }
        header {
            background-color: #343a40;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #ff5733;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            background: url('restaurant.jpg') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }
        .hero h1 {
            font-size: 3em;
        }
        .content {
            padding: 20px;
            text-align: center;
        }
        .menu-section {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        .menu-item {
            background-color: #ffffff;
            border: 1px solid #ddd;
            border-radius: 8px;
            width: 30%;
            margin: 10px;
            padding: 15px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .menu-item img {
            max-width: 100%;
            border-radius: 8px;
        }
        footer {
            background-color: #343a40;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>Casendra Restaurant</h1>
    <p>Your favorite food spot at Saveetha Engineering College!</p>
</header>

<nav>
    <a href="#about">About Us</a>
    <a href="#menu">Menu</a>
    <a href="#contact">Contact</a>
</nav>

<div class="hero">
    <h1>Delicious Food, Great Ambiance</h1>
    <p>Experience the best dining at Casendra.</p>
</div>

<div class="content">
    <section id="about">
        <h2>About Us</h2>
        <p>Casendra is the go-to destination for students and staff of Saveetha Engineering College to enjoy a wide variety of delicious dishes in a cozy atmosphere.</p>
    </section>

    <section id="menu">
        <h2>Our Menu</h2>
        <div class="menu-section">
            <div class="menu-item">
                <img src="pizza.jpg" alt="Pizza">
                <h3>Cheesy Pizza</h3>
                <p>A delightful treat loaded with cheese and toppings.</p>
            </div>
            <div class="menu-item">
                <img src="burger.jpg" alt="Burger">
                <h3>Juicy Burgers</h3>
                <p>Perfectly grilled burgers with fresh ingredients.</p>
            </div>
            <div class="menu-item">
                <img src="pasta.jpg" alt="Pasta">
                <h3>Creamy Pasta</h3>
                <p>Indulge in the rich and creamy flavors of our pasta.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: contact@casendra.com</p>
        <p>Phone: +91 98765 43210</p>
        <p>Location: Saveetha Engineering College Campus</p>
    </section>
</div>

<footer>
    <p>&copy; 2024 Casendra Restaurant. All rights reserved.</p>
</footer>

</body>
</html>


```

## OUTPUT:
![alt text](<Screenshot 2024-12-24 232444.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
