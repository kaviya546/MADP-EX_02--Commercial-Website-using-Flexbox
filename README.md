# Ex02 Commercial Website
## Date:06.08.25

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
## ABOUT.HTML:
```
about.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>About Us - Glow & Shine</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Glow & Shine Skincare</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="contact.html">Contact</a></li>
                <li><a href="account.html">Account</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Us</h2>
        <p>At Glow & Shine, we believe in natural and effective skincare solutions.</p>
    </section>

    <footer>
        <p>&copy; 2025 Glow & Shine | Follow us on social media</p>
        <div class="social-links">
            <a href="#">Facebook</a>
            <a href="#">Instagram</a>
            <a href="#">Twitter</a>
        </div>
    </footer>
</body>
</html>
```
## ACCOUNT.HTML
```
about.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>About Us - Glow & Shine</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Glow & Shine Skincare</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="contact.html">Contact</a></li>
                <li><a href="account.html">Account</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Us</h2>
        <p>At Glow & Shine, we believe in natural and effective skincare solutions.</p>
    </section>

    <footer>
        <p>&copy; 2025 Glow & Shine | Follow us on social media</p>
        <div class="social-links">
            <a href="#">Facebook</a>
            <a href="#">Instagram</a>
            <a href="#">Twitter</a>
        </div>
    </footer>
</body>
</html>
```
## CONTACT.HTML
```
contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contact - Glow & Shine</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Glow & Shine Skincare</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="contact.html">Contact</a></li>
                <li><a href="account.html">Account</a></li>
            </ul>
        </nav>
    </header>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: support@glowshine.com</p>
    </section>

    <footer>
        <p>&copy; 2025 Glow & Shine | Follow us on social media</p>
        <div class="social-links">
            <a href="#">Facebook</a>
            <a href="#">Instagram</a>
            <a href="#">Twitter</a>
        </div>
    </footer>
</body>
</html>
```
## INDEX.HTML
```
index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Glow & Shine - Home</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Glow & Shine Skincare</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="contact.html">Contact</a></li>
                <li><a href="account.html">Account</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Welcome to Glow & Shine</h2>
        <p>Discover the best skincare products for radiant and healthy skin.</p>
        <img src="1.jpg" alt="Skincare products" width="300">
    </section>

    <footer>
        <p>&copy; 2025 Glow & Shine | Follow us on social media</p>
        <div class="social-links">
            <a href="#">Facebook</a>
            <a href="#">Instagram</a>
            <a href="#">Twitter</a>
        </div>
    </footer>
</body>
</html>
```
## PRODUCTS.HTML
```
products.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Glow & Shine - Products</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Glow & Shine Skincare</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="contact.html">Contact</a></li>
                <li><a href="account.html">Account</a></li>
            </ul>
        </nav>
    </header>

    <section id="products">
        <h2>Our Skincare Products</h2>
        <div class="product-list">
            <div class="product">
                <img src="2.jpg" alt="Moisturizer">
                <p>Moisturizing Cream</p>
                <p class="price">Rs.200</p>
                <button onclick="window.location.href='payment.html'">Buy Now</button>
            </div>
            <div class="product">
                <img src="3.jpg" alt="Serum">
                <p>Vitamin C Serum</p>
                <p class="price">Rs.300</p>
                <button onclick="window.location.href='payment.html'">Buy Now</button>
            </div>
            <div class="product">
                <img src="4.jpg" alt="Sunscreen">
                <p>Sunscreen SPF 50</p>
                <p class="price">Rs.600</p>
                <button onclick="window.location.href='payment.html'">Buy Now</button>
            </div>
            <div class="product">
                <img src="5.jpg" alt="Toner">
                <p>Hydrating Toner</p>
                <p class="price">Rs.150</p>
                <button onclick="window.location.href='payment.html'">Buy Now</button>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Glow & Shine | Follow us on social media</p>
        <div class="social-links">
            <a href="#">Facebook</a>
            <a href="#">Instagram</a>
            <a href="#">Twitter</a>
        </div>
    </footer>
</body>
</html>
```
## STYLE.CSS
```
style.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
    background-color: #f8f8f8;
}

header {
    background-color: #ffcccb;
    padding: 20px;
    font-size: 24px;
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
    background-color: #ff9999;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: white;
    font-weight: bold;
    transition: color 0.3s ease;
}

nav ul li a:hover {
    color: #660000;
}

section {
    padding: 20px;
}

.product-list {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}

.product {
    background-color: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 200px;
    transition: transform 0.3s ease;
    text-align: center;
}

.product img {
    width: 150px;
    height: 150px;
    object-fit: cover;
    border-radius: 8px;
}


.product p.price {
    font-weight: bold;
    color: #ff5733;
    margin: 10px 0;
    font-size: 18px;
}

.product:hover {
    transform: scale(1.05);
}

.product button {
    background-color: #ff5733;
    color: white;
    border: none;
    padding: 10px;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
    margin-top: 10px;
    width: 100%;
}

.product button:hover {
    background-color: #cc4625;
}

footer {
    background-color: #ff9999;
    padding: 10px;
    color: white;
    margin-top: 20px;
}

.social-links {
    margin-top: 10px;
}

.social-links a {
    margin: 0 10px;
    text-decoration: none;
    color: white;
    font-size: 18px;
    transition: color 0.3s ease;
}

.social-links a:hover {
    color: #660000;
}

img {
    max-width: 100%;
    height: auto;
}

```

## OUTPUT:
![WhatsApp Image 2025-08-06 at 21 51 40_d296f4b4](https://github.com/user-attachments/assets/f57cb040-565d-4051-9b7e-a7853d662fc2)
![WhatsApp Image 2025-08-06 at 21 51 53_5c2070ce](https://github.com/user-attachments/assets/1124ce83-2585-4c14-843d-a27b94dccad8)
![WhatsApp Image 2025-08-06 at 21 52 18_095c0061](https://github.com/user-attachments/assets/a43b7629-11a2-4669-a2b4-8f1e391ba4d7)

![WhatsApp Image 2025-08-06 at 21 52 33_7b656eb8](https://github.com/user-attachments/assets/1f207488-cf9f-4461-ad3e-06fb65fca176)


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
