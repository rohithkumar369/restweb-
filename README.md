# Ex.04 Restaurant Website
## Date:26-05-2026
Name:s.rohith kumar
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
index.html


<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<header>
<nav>
    <ul style="list-style: none; display: flex; gap: 20px; justify-content: center; padding: 0;">
      <li><a href="about.html">About Us</a></li>
      <li><a href="menu.html">Menu</a></li>
      <li><a href="team.html">Team</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </nav>
  <center>
    <h1 style="font-family: cursive;"><i>Italiano Restaurant</i></h1>
</center>
</header>
<body style="background-image: url(bg1.jpg);"> 
    <section id="about" style="display: flex; justify-content: center; gap: 30px; flex-wrap: wrap; padding: 20px;">
    
   
    
        <h1 style="font-family: cursive;"><i>About Us</i></h1>
        
        <h3><b>Over 3 Decades,<i>Italiano Restaurant</i>has pioneered Italian cuisine in India. With 50 outlets in 4 countries, we are India’s largest home grown italian brand bringing you a delicious menu of Pizzas, Pastas, Appetizers, Cheeses, Wines & much more.

            Italian food is simple yet sophisticated, using few ingredients to make a dish so flavourful you keep coming back for more. Inspired by Italy’s finest family chefs, we bring you the warmth & love of Italian Cuisine directly to your home.</b></h3>
    </section>
    <div class="image-row">
        <center>
        <img src="menu1.jpg" alt="Abt" width="420" height="250">
    </center>
    </div>
    

</body>
</html>

menu.html
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Menu</title>
    <link rel="stylesheet" href="styles.css">
    <header>
        <nav>
            <ul style="list-style: none; display: flex; gap: 20px; justify-content: center; padding: 0;">
                <li><a href="index.html">About us</a></li>
                <li><a href="team.html">Team</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
        <center>
            <h1>Our Menu</h1>
        </center>
    </header>
</head>
<body style="background-image: url(bg3.jpg);"> 
<section style="display: flex; justify-content: center; gap: 30px; flex-wrap: wrap; padding: 20px;">

    <div style="text-align: center;">
      <img src="menu2.jpg" alt="" width="250">
      <h1 style="font-family: cursive;"><i>Spicy paneer tikka</i></h1>
    </div>
  
    <div style="text-align: center;">
      <img src="menu3.jpg" alt="" height="190" width="250">
      <h1 style="font-family: cursive;"><i>Chettinad chicken</i></h1>
    </div>
  
    <div style="text-align: center;">
      <img src="menu4.jpg" alt="" height="190" width="250">
      <h1 style="font-family: cursive;"><i>Mutton chuka</i></h1>
    </div>
  
    
  
    <div style="text-align: center;">
      <img src="menu7.jpg" alt="" height="190" width="250">
      <h1 style="font-family: cursive;"><i>Chicken 65</i></h1>

    </div>
    <div style="text-align: center;">
        <img src="menu11.jpg" alt="" height="190" width="250">
        <h1 style="font-family: cursive;"><i>Burger</i></h1>
      </div>
      <div style="text-align: center;">
        <img src="menu22.jpg" alt="" height="190" width="250">
        <h1 style="font-family: cursive;"><i>Donuts</i></h1>
      </div>
      <div style="text-align: center;">
        <img src="menu44.jpg" alt="" height="190" width="250">
        <h1 style="font-family: cursive;"><i>Cheese sandwich</i></h1>
      </div>
      <div style="text-align: center;">
        <img src="menu55.jpg" alt="" height="190" width="250">
        <h1 style="font-family: cursive;"><i>Pasta</i></h1>
      </div>
      <div style="text-align: center;">
        <img src="menu66.avif" alt="" height="190" width="250">
        <h1 style="font-family: cursive;"><i>Maagi</i></h1>
      </div>
      <div style="text-align: center;">
        <img src="menu77.jpg" alt="" height="190" width="250">
        <h1 style="font-family: cursive;"><i>Fruit salad</i></h1>
      </div>
  
  </section>
  </body>


  team.html

  <html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Team</title>
    <link rel="stylesheet" href="styles.css">
</head>
<header>
    <nav>
        <ul style="list-style: none; display: flex; gap: 20px; justify-content: center; padding: 0;">
            <li><a href="index.html">About us</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>
    <center>
        <h1 style="font-family: cursive;"><i>Our Team</i></h1>
    </center>
</header>
<br><br><br><br><br>
<body style="background-image: url(bg7.jpg);">
    
    <section>
        <div style="display: flex; justify-content: center; gap: 30px;">
          <div>
            <img src="myimage.jpeg" alt="Owner" height="200" width="150">
            <p><b>KESHAVARTHINI</b></p>
            <h3>(Manager)</h3>
          </div>
          <div>
            <img src="fri2.png" alt="Ops" height="200" width="150">
            <p><b>MANOJ</b></p>
            <h3>(Chef)</h3>
          </div>
          <div>
            <img src="fri3.jpg" alt="W" width="250">
            <p><b>BALAJI</b></p>
            <h3>(Assistant Chef)</h3>
          </div>
        </div>
      </section>
</body>
</html>



contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body bgcolor="silver">
    <header>
        <nav>
            <ul style="list-style: none; display: flex; gap: 20px; justify-content: center; padding: 0;">
                <li><a href="index.html">About Us</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="team.html">Team</a></li>
            </ul>
        </nav>
        <center>
            <h1>Contact Us</h1>
        </center>
    </header>

    <section>
        <center>
        <h2>Email: k56892006@gmail.com</h2>
        <h2>Phone: 9342603456</h2>
        <h2>Address: 11, Sethurayan Nagar, Kanchipuram</h2>
    </center>
    </section>

    <img src="contact.jpg" width="100%" height="350px" style="float: left; margin: 20px; border-radius: 8px;">
     <br><br><br><br><br><br><br><br><br><br>
     <center>
    <footer>
        <h4>By B KESHAVARTHINI (2122240401583)</h4>
    </footer>
</center>
</body>
</html>



index.css

body {
    background-image: url('bg2.jpg'); /* General background image */
    background-size: cover; /* Cover the entire body */
    background-repeat: no-repeat; /* Prevent the image from repeating */
    font-family: sans-serif;
    margin: 0;
    padding: 0;
}

nav {
    background-color: #f8f8f8;
    padding: 10px;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: inline-block;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
}

nav ul li a:hover {
    color: orange;
}

#about {
    background-color: orange;
    padding: 20px;
    margin: 20px;
}

#about h2 {
    color: #fff;
}

#about img {
    float: left;
    margin-right: 20px;
    margin-bottom: 10px;
    width: 420px;
    height: 250px;
}

.image-row {
    background-image: url('bg1.jpg'); /* Menu background image */
    background-size: cover;
    background-repeat: no-repeat;
    padding: 20px; /* Add padding for spacing */
    margin-top: 20px; /* Add margin to separate from the About Us section */
}

.image-row img { /* Style for the food image within the image-row */
    display: block; /* Make the image a block-level element */
    margin: 0 auto;  /* Center the image horizontally */
    width: auto;     /* Let the width adjust automatically */
    height: auto;    /* Let the height adjust automatically */
    max-width: 100%; /* Ensure the image doesn't exceed the container's width */
    max-height: 100%;/* Ensure the image doesn't exceed the container's height */
}


contact.css

body {
    background: linear-gradient(to right, #e0f7fa, #ffffff);
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    padding: 0;
    color: #333;
}

header {
    background-color: #00796b;
    color: white;
    padding: 30px 0;
    text-align: center;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

h1 {
    font-size: 2.5rem;
    margin: 0;
}

nav ul {
    display: flex;
    justify-content: center;
    padding: 10px;
    background-color: #004d40;
    margin: 0;
    list-style: none;
}

nav ul li {
    margin: 0 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #ffcc00;
}

section {
    background-color: white;
    max-width: 800px;
    margin: 40px auto;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
}

footer {
    background-color: #00796b;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 40px;
}

img {
    display: block;
    margin: 20px auto;
    border-radius: 8px;
    max-width: 100%;
}


style.css

.menu {
    display: flex;
    flex-direction: row;
    justify-content: space-around; /* or center */
    align-items: center;
    padding: 20px;
    flex-wrap: wrap; /* allows wrapping if screen is small */
  }
  
  .menu-item {
    text-align: center;
    margin: 10px;
  }
  
  .menu-item img {
    width: 150px;  /* adjust as needed */
    height: auto;
    display: block;
    margin: 0 auto;
  }
  
  .menu-item p {
    font-weight: bold;
    font-size: 16px;
    margin-top: 10px;
  }
```

## OUTPUT:
![Screenshot (127)](https://github.com/user-attachments/assets/9d68ee72-42f8-4af8-b7ee-004dbfafd31f)
![Screenshot (128)](https://github.com/user-attachments/assets/3b229383-49e3-4d7c-a67a-ed74da70bdd9)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
