# Ex.07 Restaurant Website
## Date:13/12/2024

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


## index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>saturn</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="home-header">
        <div class="banner">
            <h1>saturn</h1>
            <p>Delightful Food, Memorable Experiences</p>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="welcome">
            <h2>Welcome to saturn</h2>
            <p>Discover the finest dishes crafted with passion and precision, served with love to tantalize your taste buds.</p>
        </section>
        <section class="featured">
            <h2>Our Specialties</h2>
            <div class="featured-items">
                <div class="featured-item">
                    <img src="GS.jpeg" alt="Grilled Salmon">
                    <p>Grilled Salmon</p>
                </div>
                <div class="featured-item">
                    <img src="PM.jpeg" alt="Margherita Pizza">
                    <p>Margherita Pizza</p>
                </div>
                <div class="featured-item">
                    <img src="CLC.jpeg" alt="Chocolate Lava Cake">
                    <p>Chocolate Lava Cake</p>
                </div>
            </div>
        </section>
    </main>
    <footer>
        <p>Designed by THAVANESH B | saturn© 2024</p>
    </footer>
</body>
</html>
```
## contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - saturn</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="banner">
            <h1>saturn</h1>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Contact Us</h2>
        <p>Address: 123 Culinary Street, Foodie Town, FL 56789</p>
        <p>Phone: (123) 456-7890</p>
        <p>Email: contact@saturn.com</p>
    </main>
    <footer>
        <p>Designed by THAVANESH B | saturn © 2024</p>
    </footer>
</body>
</html>
```
## menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - saturn</title>
    <link rel="stylesheet" href="styless.css">
</head>
<body>
    <header>
        <div class="banner">
            <h1>saturn</h1>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Our Menu</h2>
        <div class="menu-card">
            <div class="menu-item">
                <img src="GS.jpeg" alt="Grilled Salmon">
                <div class="menu-details">
                    <h3>Grilled Salmon</h3>
                    <p>Freshly grilled salmon served with a lemon butter sauce.</p>
                    <p class="price">Rs 599</p>
                </div>
            <div class="menu-item">
                <img src="PM.jpeg" alt="Margherita Pizza">
                <div class="menu-details">
                    <h3>Margherita Pizza</h3>
                    <p>Wood-fired pizza topped with fresh mozzarella and basil.</p>
                    <p class="price">Rs 549</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="TC.jpeg" alt="Tandoori Chicken">
                <div class="menu-details">
                    <h3>Tandoori Chicken</h3>
                    <p>Marinated chicken cooked in a traditional clay oven.</p>
                    <p class="price">Rs 499</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="CLC.jpeg" alt="Chocolate Lava Cake">
                <div class="menu-details">
                    <h3>Chocolate Lava Cake</h3>
                    <p>Rich chocolate cake with a molten center served with ice cream.</p>
                    <p class="price">Rs 199</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="VB.jpeg" alt="Veggie Burger">
                <div class="menu-details">
                    <h3>Veggie Burger</h3>
                    <p>A delicious plant-based burger served with crispy fries.</p>
                    <p class="price">Rs 399</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="CS.jpeg" alt="Caesar Salad">
                <div class="menu-details">
                    <h3>Caesar Salad</h3>
                    <p>Fresh Romaine lettuce with Caesar dressing, croutons, and Parmesan.</p>
                    <p class="price">Rs 249</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="FF.jpeg" alt="French Fries">
                <div class="menu-details">
                    <h3>French Fries</h3>
                    <p>Golden, crispy fries served with your choice of dipping sauces.</p>
                    <p class="price">Rs 99</p>
                </div>
            </div>
        </div>
    </main>
    <footer>
        <p>Designed by THAVANESH B | saturn © 2024</p>
    </footer>
</body>
</html>
```
## administartion.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - saturn</title>
    <link rel="stylesheet" href="sty.css">
</head>
<body>
    <header>
        <div class="banner">
            <h1>saturn</h1>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <div class="admin-container">
            <div class="admin-header">
                <h2>Meet Our Team</h2>
                <p>Our exceptional team is dedicated to delivering the finest dining experience with expertise and passion.</p>
            </div>
            <div class="admin-grid">
                <!-- Team Member 1 -->
                <div class="admin-card">
                    <img src="JOHN.jpeg" alt="John Davidson">
                    <h3>John Doe</h3>
                    <p>General Manager</p>
                    <p class="experience">John has over 15 years of experience in hospitality management, ensuring excellence in every detail of our service.</p>
                </div>
                <!-- Team Member 2 -->
                <div class="admin-card">
                    <img src="JANE.jpeg" alt="Jane Smith">
                    <h3>Jane Smith</h3>
                    <p>Head Chef</p>
                    <p class="experience">Jane is a culinary expert with a passion for innovative dishes, leading our kitchen with creativity and precision.</p>
                </div>
                <!-- Team Member 3 -->
                <div class="admin-card">
                    <img src="DK.jpeg" alt="DHANUSH KUMAR">
                    <h3>Mithun Kumar</h3>
                    <p>Pastry Chef</p>
                    <p class="experience">Mithun specializes in desserts, creating memorable sweet treats that delight our guests every day.</p>
                </div>
             
                </div>
            </div>
        </div>
    </main>
    <footer>
        <p>Designed by THAVANESH B | saturn © 2024</p>
    </footer>
</body>
</html>
```





## OUTPUT:

![alt text](<Screenshot (55).png>)
![alt text](<Screenshot (52).png>)
![alt text](<Screenshot (53).png>)
![alt text](<Screenshot (54).png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
