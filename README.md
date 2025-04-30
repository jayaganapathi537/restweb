# Ex.07 Restaurant Website
## Date: 30/04/2025

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
HOME.html
``` 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Delicious Bites - Home</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
    <style>
        body {
            font-family: 'Segoe UI', sans-serif;
            margin: 0;
            background: #fff8f0;
            color: #333;
        }
        header {
            background: linear-gradient(90deg, #ff7e5f, #feb47b);
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            background: url('https://images.unsplash.com/photo-1600891964599-f61ba0e24092?ixlib=rb-4.0.3&auto=format&fit=crop&w=1950&q=80') center/cover no-repeat;
            height: 70vh;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
            background-blend-mode: multiply;
            background-color: rgba(0, 0, 0, 0.5);
            flex-direction: column;
        }
        .hero h2 {
            font-size: 3rem;
            margin: 0;
        }
        .hero p {
            font-size: 1.3rem;
            margin: 1rem 0;
        }
        .cta-button {
            padding: 0.8rem 1.5rem;
            font-size: 1rem;
            background-color: #ff7e5f;
            border: none;
            color: white;
            border-radius: 5px;
            cursor: pointer;
        }
        .cta-button:hover {
            background-color: #e65c3e;
        }
        main {
            padding: 2rem;
            text-align: center;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 1rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Delicious Bites</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="dishes.html">Menu</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
    <section class="hero">
        <h2>Welcome to Delicious Bites!</h2>
        <p>Crafting unforgettable tastes every day</p>
        <a href="dishes.html"><button class="cta-button">View Menu</button></a>
    </section>
    <main>
        <h3>Why choose us?</h3>
        <p>From farm-fresh ingredients to artful presentation, we bring passion to every plate.</p>
    </main>
    <footer>
        <p>&copy; 2025 Delicious Bites. All rights reserved.</p>
    </footer>
</body>
</html>
```
DISHES.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Delicious Bites - Menu</title>
    <style>
        body {
            font-family: 'Segoe UI', sans-serif;
            margin: 0;
            background: #fff0f5;
            color: #222;
        }
        header {
            background: linear-gradient(90deg, #ff6a00, #ee0979);
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 2rem;
        }
        h2 {
            text-align: center;
            color: #b30059;
        }
        .menu-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            max-width: 1000px;
            margin: auto;
        }
        .dish-card {
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
            overflow: hidden;
            transition: transform 0.2s;
        }
        .dish-card:hover {
            transform: scale(1.03);
        }
        .dish-card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }
        .dish-info {
            padding: 1rem;
        }
        .dish-info h3 {
            margin: 0 0 0.5rem 0;
            color: #cc005f;
        }
        .dish-info p {
            margin: 0;
        }
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 1rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Delicious Bites</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="dishes.html">Menu</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
    <main>
        <h2>Our Menu</h2>
        <div class="menu-grid">
            <div class="dish-card">
                <img src="Spaghetti Carbonara.jpg" alt="Spaghetti Carbonara">
                <div class="dish-info">
                    <h3>Spaghetti Carbonara</h3>
                    <p>₹569</p>
                </div>
            </div>
            <div class="dish-card">
                <img src="Grilled Salmon.jpg" alt="Grilled Salmon">
                <div class="dish-info">
                    <h3>Grilled Salmon</h3>
                    <p>₹499</p>
                </div>
            </div>
            <div class="dish-card">
                <img src="Margherita Pizza.jpg" alt="Margherita Pizza">
                <div class="dish-info">
                    <h3>Margherita Pizza</h3>
                    <p>₹699</p>
                </div>
            </div>
            <div class="dish-card">
                <img src="Chocolate Lava Cake (2).jpg" alt="Chocolate Lava Cake">
                <div class="dish-info">
                    <h3>Chocolate Lava Cake</h3>
                    <p>₹299</p>
                </div>
            </div>
        </div>
    </main>
    <footer>
        <p>&copy; 2025 Delicious Bites. All rights reserved.</p>
    </footer>
</body>
</html>
```
CONTACT.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Delicious Bites - Contact</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
    <style>
        body {
            font-family: 'Segoe UI', sans-serif;
            margin: 0;
            background: #f0faff;
            color: #004d40;
        }
        header {
            background: linear-gradient(90deg, #00c6ff, #0072ff);
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 3rem 2rem;
            max-width: 800px;
            margin: auto;
        }
        h2 {
            text-align: center;
            color: #00695c;
        }
        .contact-box {
            display: flex;
            flex-direction: column;
            gap: 2rem;
            margin-top: 2rem;
        }
        .contact-item {
            display: flex;
            align-items: center;
            gap: 1rem;
            font-size: 1.2rem;
            background: white;
            padding: 1rem;
            border-left: 6px solid #0072ff;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        .contact-item i {
            font-size: 1.5rem;
            color: #0072ff;
        }
        .thank-you-graphic {
            margin-top: 3rem;
            text-align: center;
        }
        .thank-you-graphic img {
            width: 250px;
            border-radius: 10px;
        }
        footer {
            background: #004d40;
            color: white;
            text-align: center;
            padding: 1rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Delicious Bites</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="dishes.html">Menu</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
    <main>
        <h2>Get in Touch</h2>
        <div class="contact-box">
            <div class="contact-item">
                <i class="fas fa-phone-alt"></i>
                <span>9653216485</span>
            </div>
            <div class="contact-item">
                <i class="fas fa-envelope"></i>
                <span>info@deliciousbites.com</span>
            </div>
            <div class="contact-item">
                <i class="fas fa-map-marker-alt"></i>
                <span>123 Spice Street, Chennai, India</span>
            </div>
        </div>
        <div class="thank-you-graphic">
            <img src="https://i.imgur.com/dZ4pW1U.png" alt="Thank You">
        </div>
    </main>
    <footer>
        <p>&copy; 2025 Delicious Bites. All rights reserved.</p>
    </footer>
</body>
</html>
```

## OUTPUT:

![alt text](<bluemittai/restapp/static/Screenshot 2025-04-30 222243.png>)
![alt text](<bluemittai/restapp/static/Screenshot 2025-04-30 222406.png>)
![alt text](<bluemittai/restapp/static/Screenshot 2025-04-30 222420.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
