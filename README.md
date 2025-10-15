# Ex.07 Restaurant Website
## Date:15/10/25

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
admin.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Admin Dashboard - Sanju Restaurant</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Great+Vibes&display=swap');

    body {
      font-family: 'Playfair Display', serif;
      margin: 0;
      background-color: #fffaf2;
      color: #3e2c1c;
    }

    header {
      background-color: #3e2c1c;
      color: #f8e3a1;
      text-align: center;
      padding: 25px 0;
      font-size: 2.2em;
      font-family: 'Great Vibes', cursive;
    }

    nav {
      background-color: #b69155;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 14px 0;
    }

    nav a {
      color: #fffaf2;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1em;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #3e2c1c;
    }

    .dashboard {
      max-width: 900px;
      margin: 40px auto;
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      padding: 30px;
    }

    .dashboard h2 {
      color: #b69155;
      margin-bottom: 10px;
      border-bottom: 2px solid #b69155;
      display: inline-block;
      padding-bottom: 5px;
    }

    ul {
      list-style-type: none;
      padding: 0;
      margin: 15px 0;
    }

    li {
      padding: 8px 0;
      border-bottom: 1px solid #eee;
    }

    form {
      margin-top: 20px;
    }

    input {
      padding: 8px;
      margin-right: 10px;
      border: 1px solid #b69155;
      border-radius: 6px;
    }

    button {
      background-color: #b69155;
      color: #fffaf2;
      border: none;
      padding: 10px 18px;
      border-radius: 6px;
      cursor: pointer;
      transition: background-color 0.3s;
    }

    button:hover {
      background-color: #3e2c1c;
    }

    footer {
      background-color: #3e2c1c;
      color: #f8e3a1;
      text-align: center;
      padding: 15px;
      margin-top: 50px;
    }
  </style>
</head>
<body>
<header>Sanju Restaurant - Dashboard</header>

<nav>
  <a href="rest.html">Home</a>
  <a href="menu.html">Menu</a>
  <a href="contact.html">Contact</a>
  <a href="rest.html">Logout</a>
</nav>

<section class="dashboard">
  <h2>Available Dishes</h2>
  <ul>
    <li>Burger</li>
    <li>Corndog</li>
    <li>Momos</li>
    <li>Pancake</li>
    <li>Chicken Biryani</li>
    <li>Dosa</li>
    <li>Meals</li>
    <li>Pani Poori</li>
    <li>Prawn</li>
    <li>Sandwich</li>
    <li>Butter Chicken</li>
    <li>Chicken Wings</li>
  </ul>

  <h2>Add New Dish</h2>
  <form>
    <input type="text" placeholder="Dish Name">
    <input type="text" placeholder="Price">
    <button type="submit">Add Dish</button>
  </form>

  <h2>Employees on Shift</h2>
  <ul>
    <li>Raj - Chef</li>
    <li>Ajay - Waiter</li>
    <li>Mithran - Manager</li>
  </ul>
</section>

<footer>© 2025 Sanju Restaurant</footer>
</body>
</html>

booking.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Book a Table - Sanju Restaurant</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Great+Vibes&display=swap');

    body {
      font-family: 'Playfair Display', serif;
      margin: 0;
      background-color: #fffaf2;
      color: #3e2c1c;
    }

    header {
      background-color: #3e2c1c;
      color: #f8e3a1;
      text-align: center;
      padding: 25px 0;
      font-size: 2.2em;
      font-family: 'Great Vibes', cursive;
    }

    nav {
      background-color: #b69155;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 14px 0;
    }

    nav a {
      color: #fffaf2;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1em;
    }

    nav a:hover {
      color: #3e2c1c;
    }

    .booking-form {
      max-width: 600px;
      margin: 50px auto;
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      padding: 30px;
    }

    .booking-form h2 {
      text-align: center;
      color: #b69155;
      font-size: 2em;
      margin-bottom: 25px;
    }

    label {
      display: block;
      margin-bottom: 8px;
      font-weight: 600;
      color: #3e2c1c;
    }

    input, select {
      width: 100%;
      padding: 10px;
      margin-bottom: 18px;
      border: 1px solid #b69155;
      border-radius: 6px;
      font-size: 1em;
    }

    button {
      width: 100%;
      background-color: #b69155;
      color: #fffaf2;
      border: none;
      padding: 12px;
      border-radius: 6px;
      font-size: 1.1em;
      cursor: pointer;
    }

    button:hover {
      background-color: #3e2c1c;
    }

    footer {
      background-color: #3e2c1c;
      color: #f8e3a1;
      text-align: center;
      padding: 15px;
      margin-top: 50px;
    }
  </style>
</head>
<body>
  <header>Sanju Restaurant</header>
  <nav>
    <a href="rest.html">Home</a>
    <!-- <a href="about.html">About</a> -->
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="booking.html">Book Table</a>
  </nav>

  <section class="booking-form">
    <h2>Book a Table</h2>
    <form action="#" method="POST">
      <label for="name">Full Name</label>
      <input type="text" id="name" required>

      <label for="email">Email</label>
      <input type="email" id="email" required>

      <label for="phone">Phone Number</label>
      <input type="tel" id="phone" required>

      <label for="guests">Number of Guests</label>
      <input type="number" id="guests" min="1" required>

      <label for="date">Date</label>
      <input type="date" id="date" required>

      <label for="time">Time</label>
      <input type="time" id="time" required>

      <button type="submit">Book Now</button>
    </form>
  </section>

  <footer>© 2025 Designed by Sanjutha</footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us - Sanju Restaurant</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Great+Vibes&display=swap');
    body {
      font-family: 'Playfair Display', serif;
      margin: 0;
      background-color: #fffaf2;
      color: #3e2c1c;
    }

    header {
      background-color: #3e2c1c;
      color: #f8e3a1;
      text-align: center;
      padding: 25px 0;
      font-size: 2.2em;
      font-family: 'Great Vibes', cursive;
    }

    nav {
      background-color: #b69155;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 14px 0;
    }

    nav a {
      color: #fffaf2;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1em;
    }

    nav a:hover {
      color: #3e2c1c;
    }

    .contact {
      text-align: center;
      padding: 60px 20px;
    }

    .contact h2 {
      color: #b69155;
      font-size: 2.2em;
      margin-bottom: 20px;
    }

    .contact p {
      font-size: 1.2em;
      margin-bottom: 10px;
    }

    footer {
      background-color: #3e2c1c;
      color: #f8e3a1;
      text-align: center;
      padding: 15px;
      margin-top: 50px;
    }
  </style>
</head>
<body>
  <header>Sanju Restaurant</header>
  <nav>
    <a href="rest.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="admin.html">Administration</a>
  </nav>

  <section class="contact">
    <h2>Contact Us</h2>
    <p>📍 No.4/3 North Street , Perangiyur , Villupuram</p>
    <p>📞 +91 8220490558</p>
    <p>📧 Email: Sanjutha@gmail.com</p>
  </section>

  <footer>© 2025 Sanju Restaurant</footer>
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Our Menu - Sanju Restaurant</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Great+Vibes&display=swap');
    body {
      font-family: 'Playfair Display', serif;
      margin: 0;
      background-color: #fffaf2;
      color: #3e2c1c;
    }

    header {
      background-color: #3e2c1c;
      color: #f8e3a1;
      text-align: center;
      padding: 25px 0;
      font-size: 2.2em;
      font-family: 'Great Vibes', cursive;
    }

    nav {
      background-color: #b69155;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 14px 0;
    }

    nav a {
      color: #fffaf2;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1em;
    }

    nav a:hover {
      color: #3e2c1c;
    }

    .menu {
      text-align: center;
      padding: 50px 20px;
    }

    .menu h2 {
      font-size: 2.2em;
      color: #b69155;
      margin-bottom: 40px;
    }

    .menu-gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
    }

    .menu-gallery img {
      width: 250px;
      height: 200px;
      border-radius: 12px;
      object-fit: cover;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s;
    }

    .menu-gallery img:hover {
      transform: scale(1.05);
    }

    footer {
      background-color: #3e2c1c;
      color: #f8e3a1;
      text-align: center;
      padding: 15px;
      margin-top: 50px;
    }
  </style>
</head>
<body>
  <header>Sanju Restaurant</header>

  <nav>
    <a href="rest.html">Home</a>
    <!-- <a href="about.html">About</a> -->
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="booking.html">Book Table</a>
  </nav>

  <section class="menu">
    <h2>Our Delicious Dishes</h2>
    <div class="menu-gallery">
      <img src="food1.jpeg" alt="Dish 1">
      <img src="food2.jpeg" alt="Dish 2">
      <img src="food3.jpeg" alt="Dish 3">
      <img src="food4.jpeg" alt="Dish 4">
      <img src="food5.jpeg" alt="Dish 5">
      <img src="food6.jpeg" alt="Dish 6">
    </div>
  </section>

  <footer>© 2025 Designed by Sanjutha</footer>
</body>
</html>

rest.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sanjutha Restaurant</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Great+Vibes&display=swap');

    body {
      font-family: 'Playfair Display', serif;
      margin: 0;
      background-color: #fffaf2;
      color: #3e2c1c;
    }

    header {
      background-color: #3e2c1c;
      color: #f8e3a1;
      text-align: center;
      padding: 25px 0;
      font-size: 2.2em;
      font-family: 'Great Vibes', cursive;
      letter-spacing: 1px;
    }

    nav {
      background-color: #b69155;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 14px 0;
    }

    nav a {
      color: #fffaf2;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1em;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #3e2c1c;
    }

    section.About {
      text-align: center;
      padding: 50px 20px;
    }

    section.About h1 {
      font-size: 2.5em;
      color: #b69155;
      margin-bottom: 10px;
    }

    section.About p {
      font-size: 1.2em;
      color: #6d4b31;
      margin-bottom: 40px;
    }

    .staff-gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 25px;
      padding: 20px;
    }

    .staff-gallery img {
      width: 220px;
      height: 220px;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.15);
      transition: transform 0.3s, box-shadow 0.3s;
      object-fit: cover;
    }

    .staff-gallery img:hover {
      transform: scale(1.05);
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.25);
    }

    footer {
      background-color: #3e2c1c;
      color: #f8e3a1;
      text-align: center;
      padding: 15px 10px;
      font-size: 1em;
      letter-spacing: 0.5px;
      margin-top: 40px;
    }

    @media (max-width: 768px) {
      nav {
        flex-direction: column;
        gap: 15px;
      }
      .staff-gallery img {
        width: 160px;
        height: 160px;
      }
    }
  </style>
</head>
<body>
  <header>Sanjutha Restaurant</header>

  <nav>
    <a href="rest.html">Home</a>
    <!-- <a href="about.html">About</a> -->
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="booking.html">Book Table</a>
  </nav>

  <section id="About" class="About">
    <h1>Welcome to Sanju Restaurant</h1>
    <p>Meet our dedicated and talented staff members</p>

    <div class="staff-gallery">
      <img src="actor1.jpeg" alt="Staff 1">
      <img src="actor2.jpeg" alt="Staff 2">
      <img src="actor3.jpeg" alt="Staff 3">
      <img src="actor4.jpeg" alt="Staff 4">
      <img src="actor5.jpg" alt="Staff 5">
    </div>
  </section>

  <footer>
    © 2025 Designed by Sanjutha
  </footer>
</body>
</html>

```

## OUTPUT:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/060c91eb-ee3c-4c53-914c-d167ad61a711" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/05770f8a-d154-4026-944e-71dcae0d9117" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2edd5fc7-c4e5-4bfb-8a94-6eff13fb3ee1" />
<img width="1280" height="719" alt="image" src="https://github.com/user-attachments/assets/ba489d40-cac5-40c4-963b-f4f66fc9fa7c" />
<img width="1280" height="719" alt="image" src="https://github.com/user-attachments/assets/c922379d-a657-4a32-ab11-279294562906" />



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
