# Ex02 Commercial Website
## Date:

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

### index.html



```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FoodieHub | Delicious Food</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- Navigation Bar -->
    <header>
        <div class="logo">🍽 FoodieHub</div>

        <nav>
            <a href="#home">Home</a>
            <a href="#menu">Menu</a>
            <a href="#about">About Us</a>
            <a href="#contact">Contact</a>
        </nav>

        <a href="#menu" class="header-btn">Order Now</a>
    </header>

    <!-- Home Section -->
    <section class="hero" id="home">

        <div class="hero-content">

            <span class="tag">WELCOME TO FOODIEHUB</span>

            <h1>Taste the Tradition,<br>Served Fresh Daily</h1>

            <p>
                Where authentic taste meets modern dining.
                Experience freshness, tradition, and delicious
                flavours in every meal.
            </p>

            <div class="hero-buttons">
                <a href="#menu" class="primary-btn">Order Now</a>
                <a href="#menu" class="secondary-btn">Explore Menu</a>
            </div>

            <div class="features">
                <div>
                    <h3>50K+</h3>
                    <p>Happy Customers</p>
                </div>

                <div>
                    <h3>4.9 ★</h3>
                    <p>Customer Rating</p>
                </div>

                <div>
                    <h3>30 min</h3>
                    <p>Fast Delivery</p>
                </div>
            </div>

        </div>

        <div class="hero-image">
            <img src="https://images.unsplash.com/photo-1547592180-85f173990554?w=900"
                 alt="Fresh and delicious food">
        </div>

    </section>

    <!-- Menu Section -->
    <section class="menu-section" id="menu">

        <div class="section-heading">
            <span class="tag">OUR SPECIALITIES</span>
            <h2>Explore Our Delicious Menu</h2>
            <p>Freshly prepared meals made with love.</p>
        </div>

        <div class="food-container">

            <div class="food-card">
                <img src="https://images.unsplash.com/photo-1513104890138-7c749659a591?w=500"
                     alt="Margherita Pizza">
                <span class="food-tag">Popular</span>
                <h3>Margherita Pizza</h3>
                <p>Fresh cheese, tomato and herbs.</p>
                <div class="food-bottom">
                    <h4>₹249</h4>
                    <button>Order Now</button>
                </div>
            </div>

            <div class="food-card">
                <img src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd?w=500"
                     alt="Classic Burger">
                <span class="food-tag">Best Seller</span>
                <h3>Classic Burger</h3>
                <p>Juicy burger with fresh vegetables.</p>
                <div class="food-bottom">
                    <h4>₹149</h4>
                    <button>Order Now</button>
                </div>
            </div>

            <div class="food-card">
                <img src="https://images.unsplash.com/photo-1473093295043-cdd812d0e601?w=500"
                     alt="Italian Pasta">
                <span class="food-tag">Chef's Choice</span>
                <h3>Italian Pasta</h3>
                <p>Creamy pasta with delicious sauce.</p>
                <div class="food-bottom">
                    <h4>₹199</h4>
                    <button>Order Now</button>
                </div>
            </div>

            <div class="food-card">
                <img src="https://images.unsplash.com/photo-1547592180-85f173990554?w=500"
                     alt="Fresh Salad">
                <span class="food-tag">Healthy</span>
                <h3>Fresh Salad</h3>
                <p>Fresh vegetables and healthy greens.</p>
                <div class="food-bottom">
                    <h4>₹129</h4>
                    <button>Order Now</button>
                </div>
            </div>

            <div class="food-card">
                <img src="https://images.unsplash.com/photo-1565299624946-b28f40a0ae38?w=500"
                     alt="Special Pizza">
                <span class="food-tag">Popular</span>
                <h3>Special Pizza</h3>
                <p>Pizza with fresh and tasty toppings.</p>
                <div class="food-bottom">
                    <h4>₹299</h4>
                    <button>Order Now</button>
                </div>
            </div>

            <div class="food-card">
                <img src="https://images.unsplash.com/photo-1551024506-0bccd828d307?w=500"
                     alt="Sweet Dessert">
                <span class="food-tag">Sweet Treat</span>
                <h3>Sweet Dessert</h3>
                <p>A delightful dessert for everyone.</p>
                <div class="food-bottom">
                    <h4>₹99</h4>
                    <button>Order Now</button>
                </div>
            </div>

            <div class="food-card">
                <img src="https://images.unsplash.com/photo-1569718212165-3a8278d5f624?w=500"
                     alt="Noodles">
                <span class="food-tag">Special</span>
                <h3>Special Noodles</h3>
                <p>Hot and flavourful noodles.</p>
                <div class="food-bottom">
                    <h4>₹159</h4>
                    <button>Order Now</button>
                </div>
            </div>

            <div class="food-card">
                <img src="https://images.unsplash.com/photo-1567620905732-2d1ec7ab7445?w=500"
                     alt="Pancakes">
                <span class="food-tag">Favourite</span>
                <h3>Sweet Pancakes</h3>
                <p>Soft pancakes with sweet toppings.</p>
                <div class="food-bottom">
                    <h4>₹179</h4>
                    <button>Order Now</button>
                </div>
            </div>

        </div>

    </section>

    <!-- About Section -->
    <section class="about-section" id="about">

        <div class="about-image">
            <img src="https://images.unsplash.com/photo-1555939594-58d7cb561ad1?w=800"
                 alt="Restaurant food preparation">
        </div>

        <div class="about-content">
            <span class="tag">ABOUT FOODIEHUB</span>

            <h2>Good Food.<br>Good Mood.</h2>

            <p>
                At FoodieHub, we believe that every meal should
                be a memorable experience. Our food is prepared
                using fresh ingredients and delicious recipes.
            </p>

            <p>
                From classic favourites to modern dishes,
                we bring happiness to your dining experience.
            </p>

            <a href="#menu" class="primary-btn">Discover Our Menu</a>
        </div>

    </section>

    <!-- Contact Section -->
    <section class="contact-section" id="contact">

        <div class="section-heading">
            <span class="tag">GET IN TOUCH</span>
            <h2>Contact Us</h2>
            <p>We would love to hear from you!</p>
        </div>

        <div class="contact-container">

             <div class="contact-card">
                <h3>👩 Website Developer</h3>
                <p>Mrudhula CS</p>
            </div>

            <div class="contact-card">
                <h3>📞 Phone</h3>
                <p>+91 9391723057</p>
            </div>

            <div class="contact-card">
                <h3>✉ Email</h3>
                <p>mrudhula235@gamil.com</p>
            </div>

           

        </div>

    </section>

    <!-- Footer -->
    <footer>

        <div class="footer-content">

            <div>
                <h2>🍽 FoodieHub</h2>
                <p>Delicious food, happy moments.</p>
            </div>

            <div>
                <h3>Quick Links</h3>
                <a href="#home">Home</a>
                <a href="#menu">Menu</a>
                <a href="#about">About Us</a>
                <a href="#contact">Contact</a>
            </div>

            <div>
                <h3>Contact Details</h3>
                <p>Mrudhula CS</p>
                <p>+91 9391723057</p>
                <p>mrudhula235@gamil.com</p>
            </div>

        </div>

        <div class="copyright">
            <p>© 2026 FoodieHub. All Rights Reserved.</p>
            <p>Designed by Mrudhula CS</p>
        </div>

    </footer>

</body>
</html>

```

### style.css 


```css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
    scroll-padding-top: 80px;
}

body {
    font-family: Arial, sans-serif;
    background: #fffaf3;
    color: #30221b;
}

/* Navigation */

header {
    background: #fffaf3;
    padding: 20px 7%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 20px;
}

.logo {
    font-size: 27px;
    font-weight: bold;
    color: #e87516;
}

nav {
    display: flex;
    gap: 25px;
    flex-wrap: wrap;
}

nav a {
    text-decoration: none;
    color: #39251b;
    font-weight: bold;
    transition: 0.3s;
}

nav a:hover {
    color: #e87516;
}

.header-btn {
    text-decoration: none;
    color: white;
    background: #e87516;
    padding: 12px 22px;
    border-radius: 25px;
}

/* Hero Section */

.hero {
    margin: 25px auto;
    width: 90%;
    min-height: 500px;
    padding: 50px;
    background: #ffead5;
    border-radius: 20px;

    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 40px;
    flex-wrap: wrap;
}

.hero-content {
    flex: 1;
    min-width: 280px;
}

.tag {
    color: #e87516;
    font-size: 13px;
    font-weight: bold;
    letter-spacing: 2px;
}

.hero h1 {
    font-size: 45px;
    line-height: 1.2;
    margin: 25px 0;
}

.hero-content > p {
    color: #78695d;
    line-height: 1.8;
    max-width: 450px;
    margin-bottom: 25px;
}

.hero-buttons {
    display: flex;
    gap: 15px;
    flex-wrap: wrap;
}

.primary-btn,
.secondary-btn {
    display: inline-block;
    padding: 13px 25px;
    border-radius: 8px;
    text-decoration: none;
    transition: 0.3s;
}

.primary-btn {
    background: #e87516;
    color: white;
}

.secondary-btn {
    border: 1px solid #e87516;
    color: #e87516;
}

.primary-btn:hover {
    background: #b94d08;
}

.secondary-btn:hover {
    background: #ffe0bd;
}

/* Hero Image */

.hero-image {
    flex: 1;
    min-width: 280px;
    display: flex;
    justify-content: center;
}

.hero-image img {
    width: 100%;
    max-width: 430px;
    height: 380px;
    object-fit: cover;
    border-radius: 50%;
    border: 8px solid white;
}

/* Statistics */

.features {
    display: flex;
    gap: 35px;
    margin-top: 40px;
    flex-wrap: wrap;
}

.features h3 {
    color: #e87516;
    margin-bottom: 8px;
}

.features p {
    font-size: 12px;
    color: #78695d;
}

/* Menu Section */

.menu-section {
    padding: 70px 7%;
    background: #fffaf3;
}

.section-heading {
    text-align: center;
    margin-bottom: 40px;
}

.section-heading h2,
.menu-section h2 {
    font-size: 35px;
    margin: 15px 0;
}

.section-heading p,
.menu-section > p {
    color: #78695d;
}

/* Flexbox Food Cards */

.food-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 25px;
}

.food-card {
    background: white;
    width: 250px;
    padding: 15px;
    border-radius: 15px;
    box-shadow: 0 5px 20px rgba(80, 45, 15, 0.10);
    position: relative;
    transition: transform 0.3s;
}

.food-card:hover {
    transform: translateY(-8px);
}

.food-card img {
    width: 100%;
    height: 180px;
    object-fit: cover;
    border-radius: 10px;
}

.food-tag {
    display: inline-block;
    background: #fff0dc;
    color: #e87516;
    padding: 5px 10px;
    font-size: 11px;
    border-radius: 20px;
    margin-top: 12px;
}

.food-card h3 {
    margin: 12px 0;
}

.food-card p {
    font-size: 13px;
    color: #78695d;
    min-height: 35px;
}

.food-bottom {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 15px;
}

.food-bottom h4 {
    color: #e87516;
    font-size: 20px;
}

.food-card button {
    background: #e87516;
    color: white;
    border: none;
    padding: 10px 15px;
    border-radius: 7px;
    cursor: pointer;
}

.food-card button:hover {
    background: #b94d08;
}

/* About Section */

.about-section {
    background: #ffead5;
    padding: 70px 8%;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 50px;
    flex-wrap: wrap;
}

.about-image {
    flex: 1;
    min-width: 280px;
}

.about-image img {
    width: 100%;
    max-width: 450px;
    height: 350px;
    object-fit: cover;
    border-radius: 20px;
}

.about-content {
    flex: 1;
    min-width: 280px;
}

.about-content h2 {
    font-size: 40px;
    margin: 20px 0;
}

.about-content p {
    line-height: 1.8;
    color: #78695d;
    margin-bottom: 20px;
}

/* Contact Section */

.contact-section {
    padding: 70px 7%;
    background: #fffaf3;
}

.contact-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 25px;
}

.contact-card {
    background: white;
    padding: 30px;
    width: 280px;
    text-align: center;
    border-radius: 15px;
    box-shadow: 0 4px 15px rgba(80, 45, 15, 0.10);
}

.contact-card h3 {
    color: #e87516;
    margin-bottom: 15px;
}

.contact-card p {
    color: #78695d;
    overflow-wrap: anywhere;
}

/* Footer */

footer {
    background: #39251b;
    color: white;
    padding: 45px 7% 20px;
}

.footer-content {
    display: flex;
    justify-content: space-between;
    gap: 30px;
    flex-wrap: wrap;
}

.footer-content h2 {
    color: #ffad55;
    margin-bottom: 15px;
}

.footer-content h3 {
    margin-bottom: 15px;
}

.footer-content p {
    color: #e6d6c9;
    margin-bottom: 10px;
}

.footer-content a {
    display: block;
    text-decoration: none;
    color: #e6d6c9;
    margin-bottom: 10px;
}

.footer-content a:hover {
    color: #ffad55;
}

.copyright {
    border-top: 1px solid #665044;
    text-align: center;
    padding-top: 20px;
    margin-top: 30px;
    color: #e6d6c9;
    line-height: 1.8;
}

/* Responsive Design */

@media (max-width: 768px) {

    header {
        flex-direction: column;
        text-align: center;
    }

    nav {
        justify-content: center;
        gap: 15px;
    }

    .hero {
        padding: 30px 20px;
        text-align: center;
    }

    .hero h1 {
        font-size: 32px;
    }

    .hero-content > p {
        margin-left: auto;
        margin-right: auto;
    }

    .hero-buttons {
        justify-content: center;
    }

    .hero-image img {
        height: 280px;
    }

    .features {
        justify-content: center;
    }

    .about-section {
        text-align: center;
    }

    .food-card {
        width: 100%;
        max-width: 320px;
    }

    .footer-content {
        flex-direction: column;
        text-align: center;
    }
}

```



## OUTPUT


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.