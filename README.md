# Ex.07 Restaurant Website
## Date: 11-05-2025
NAME: VIJAYAKUMAR S

REG NO: 212224040359

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
    <title>Accord Restaurant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-image: url('multicuisine-restaurant-.webp');
            margin: 0;
            padding: 0;
        }
        header {
            
            background-size: cover;
            background-size: no-repeat;
            background-attachment: fixed;
            color: white;
            text-align: center;
            padding: 50px 0;
        }
        nav {
            background-color: rgba(244, 240, 240, 0.6);
            display: flex;
            justify-content: center;
            padding: 10px;
        }
        nav a {
            color: white;
            margin: 0 20px;
            text-decoration: none;
        }
        .content {
            background-color: transparent;
            margin: 20px auto;
            padding: 20px;
            max-width: 800px;
            border-radius: 8px;
            color: white;
        }
        .menu {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
            gap: 10px;
            margin-top: 20px;
        }
        .menu-item {
            background-color: rgb(16, 16, 16);
            padding: 15px;
            text-align: center;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>ACCORD RESTAURANT</h1>
        <nav>
            <a href="#">Home</a>
            <a href="#">Menu</a>
            <a href="#">About Us</a>
            <a href="#">Contact</a>
        </nav>
    </header>
    <div class="content">
        <h2>Welcome to Accord</h2>
        <p>Discover the taste of continental cuisine at Accord Restaurant. We serve an array of delicious dishes crafted with fresh ingredients and a touch of elegance. Join us for an unforgettable dining experience.</p>
        <h3>Menu</h3>
        <div class="menu">
            <div class="menu-item">Grilled Chicken Salad</div>
            <div class="menu-item">Beef Stroganoff</div>
            <div class="menu-item">Spaghetti Carbonara</div>
            <div class="menu-item">Fish and Chips</div>
            <div class="menu-item">Chicken Alfredo Pasta</div>
            <div class="menu-item">Vegetable Lasagna</div>
            <div class="menu-item">Garlic Butter Shrimp</div>
            <div class="menu-item">Roast Beef with Vegetables</div>
            <div class="menu-item">Chicken Cordon Bleu</div>
            <div class="menu-item">BBQ Ribs</div>
        </div>
    </div>
</body>
</html>

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/b6f87afd-6f39-4f86-8a52-6eda2f5a8d9a)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
