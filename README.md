# Ex.07 Restaurant Website
## Date: 13/11/24

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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Website</title>
    <style>
        /* Color Scheme */
        :root {
            --primary-color: #050f6a; 
            --secondary-color: #ddc6c6; 
            --background-color: #ffffff; 
            --text-color: #54074f;
        }
        
        /* General Styling */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: var(--background-color);
            color: var(--text-color);
        }

        header, footer {
            background-color: var(--primary-color);
            color: #FFF;
            text-align: center;
            padding: 1em;
        }

        header nav a {
            color: #FFF;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        #banner {
            text-align: center;
            padding: 20px;
        }

        #banner img {
            max-width: 100%;
            height: auto;
        }

        section {
            padding: 20px;
            max-width: 1000px;
            margin: auto;
        }

        h2 {
            color: var(--primary-color);
            text-align: center;
        }

        /* Menu Page Styling */
        #menu {
            display: flex;
            flex-wrap: nowrap; /* Ensure items stay in one row */
            gap: 20px;
            justify-content: center;
        }

        .menu-item {
            flex: 1 1 22%; /* Adjusts items to fit four in a row */
            max-width: 22%;
            background-color: #FFF;
            padding: 10px;
            text-align: center;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }

        .menu-item img {
            width: 100%;
            height: 150px;
            object-fit: cover;
        }

        /* Contact Page Styling */
        #contact-info p {
            text-align: center;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <nav>
            <a href="#banner">Home</a>
            <a href="#menu">Menu</a>
            <a href="#contact-info">Contact Us</a>
        </nav>
    </header>

    <!-- Banner Section (Home) -->
    <section id="banner">
        <img src="logo.png" alt="Restaurant Banner">
        <h4>The Original Beef Of Chicagoland</h4>
    </section>

    <!-- Menu Section -->
    <section id="menu">
        <h1> Our Menu </h1>
        
        <div class="menu-item">
            <img src="spaghetti.jpeg" alt="Chicken Wings">
            <h3>Spaghetti</h3>
            <p>Speacially made pasta in traditional way</p>
        </div>
        <div class="menu-item">
            <img src="burrito.jpeg" alt="Grill Chicken">
            <h3>Burrito</h3>
            <p>A tortilla wrapped around a mixed filling of meat, cheese and veggies</p>
        </div>
        <div class="menu-item">
            <img src="chicken rice.jpeg" alt="Chicken Rice">
            <h3>Chicken Rice</h3>
            <p>Bite-sized poached chicken served on fragrant rice, with a special chili dip</p>
        </div>
        <div class="menu-item">
            <img src="chicken noodles.jpeg" alt="Chicken Noodles">
            <h3>Chicken Noodles</h3>
            <p>Classic comfort food made with chicken, noodles, and vegetables in a clear broth</p>
        </div>
        <!-- Add more menu items similarly -->
    </section>

    <!-- Contact Us Section -->
    <section id="contact-info">
        <h2>Contact Us</h2>
        <p>Address: 666 N Orleans St Chicago</p>
        <p>Manager : Carmy Berzatto</p>
        <p>Phone: 6369977445</p>
        <p>Email: toboc@gmail.com</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Fresh & Delicious Food | Designed by Jeevan ES</p>
    </footer>

</body>
</html>
```

## OUTPUT
![Uploading Screenshot 2024-11-13 221232.png…]()


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
