# Ex.06 Restuarant Website
## Date:

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

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
        <title>
            HOME
        </title>
        <link rel="stylesheet" href="index.css">
    </head>
    <body>
        <div class="heading">
            <p><u>CHENNAI CRAVINGS<u></u></p>
        </div>
        <div class="vision">
            <p>
                Your cravings,our creation
            </p>
        </div>
        <div class="About">
            <b>"Delicious food,fresh ingrdients,and flavors you'll love"</b>
        </div>
        <div class="header">
            <a href="index.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contact</a>
        
        <div class="footer">&copy;LINGESHWARI K</div>
    </body>
</html>

index.css

body{
    background-image: url("restaurant\ home.webp");
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    margin: 0;
}
.heading{
    position: absolute;
    top: 0.5px;
    left: 0;
    right: 0;
    text-align: center;
    font-family: 'Times New Roman', Times, serif;  
    font-size: 80px;
    font-weight: bolder;
    color:beige; 
}
.about{
    position: absolute;
    top: 210px;
    left: 0;
    right: 0;
    width: 700px;
    margin: auto;
    text-align: center;
    font-family: 'Times New Roman', Times, serif;
    font-size: 35px;
    color: white;
}
a:hover{
    background-color:rgb(53, 7, 118);
    color:white;
}
.vision{
    position: absolute;
    top: 280px;
    left: 0;
    right: 0;
    text-align: center;
    font-family: 'Times New Roman', Times, serif;
    font-size: 50px;
    font-family: 'Times New Roman', Times, serif;
    color: blanchedalmond; 
}
.header{
    position: fixed;
    top: 30px;
    right: 50px;
    font-family: 'Times New Roman', Times, serif; 
    font-size: 30px;
    color:white;
}
.header a {
    text-decoration: none;
    margin-left: 20px;
    padding: 10px 15px;
    background-color: blue;
    color:white;
    font-size: 16px;
}
.img{
    position: relative;
    top: 470px;
    text-align: center;
}

.footer{
    position: fixed;
    bottom: 0;
    width: 100%;
    background-color: black; 
    color: white; 
    text-align: center;
    font-family: 'Times New Roman', Times, serif; 
    padding: 10px;
}
menu.html

<html>
<head>
    <title>MENU</title>
    <link rel="stylesheet" href="menu.css">
</head>
<body>
    <div class="nav">
        <a href="index.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>
    <h1 class="menu">MENU</h1>
    <br>
    <br>
    <br>
    <div class="container">
        <div class="list">
            <img src="burger.jpg">
            <h3>BURGER</h3>
            <p>RS.400</p>
        </div>
        <div class="list">
            <img src="pizza.jpg">
            <h3>PIZZA</h3>
            <p>Rs.500</p>
        </div>
        <div class="list">
            <img src="fries.jpg">
            <h3>FRENCH FRIES</h3>
            <p>Rs.200</p>
        </div>
        <div class="list">
            <img src="burg.jpg">
            <h3>BURGER WITH COKE</h3>
            <p>Rs.800</p>
        </div>
        <div class="list">
            <img src="fry.jpg">
            <h3>CHICKEN COMBO</h3>
            <p>Rs.750</p>
        </div>
        
        
        
    </div>
    <div class="footer">&copy;LINGESHWARI</div>
</body>
</html>

menu.css
body{
    background-image: url("restaurant\ menu.jpg");
    background-size: cover;
    background-position: center;
    font-family: 'Times New Roman', Times, serif;
}


.nav{
    position: absolute;
    top: 20px;
    right: 30px;
}

.nav a{
    text-decoration: none;
    margin-left: 20px;
    padding: 10px 15px;
    background-color: blue;
    color: WHITE;
    font-size: 16px;
}


.menu{
    position:absolute;
    top: 100px;
    text-align: center;
    left: 700px;
    font-size: 60px;
    color: rgb(0, 0, 0);
}


.container{
    position: relative;
    top: 200px;
    display: flex;
    justify-content: center;
    gap: 20px;
}


.list{
    background-color: brown;
    padding: 15px;
    text-align: center;
    border-radius: 15px;
}

.list img{
    width: 200px;
    height: 200px;
    border-radius: 15px;
}
.footer{
    position: fixed;
    bottom: 0;
    width: 100%;
    background-color: black; 
    color:white; 
    text-align: center;
    font-family: 'Times New Roman', Times, serif; 
    padding: 10px;
}

admin.html

admin.html


<html>
<head>
    <title>Admin</title>
    <link rel="stylesheet" href="admin.css">
</head>
<body>
    <div class="nav">
        <a href="index.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>
    <h1 class="admin">ADMIN</h1>
    <br>
    <br>
    <br>
    <br>
    <div class="menu">
        <div class="list">
            <img src="admin1.jpg">
            <h3> Charlie</h3> 
            <p>CEO</p>
        </div>
        <div class="list">
            <img src="admin2.jpg">
            <h3>Jamie </h3>
            <p>Manager</p>
            
        </div>
        <div class="list">
            <img src="admin3.jpg">
            <h3>Dakota</h3>
            <p>Assistant Manager </p>
        </div>
        <div class="list">
            <img src="admin 4.jpg">
            <h3>Ash</h3>
            <p>HR Manager</p>
        </div>
        <div class="list">
            <img src="admin 5.jpg">
            <h3>Milan</h3>
            <p>Chef</p>
        </div>
    </div>
    <div class="footer">&copy;LINGESHWARI </div>
</body>
</html>

admin.css

body{
    background-image: url("ADMIN.jpg");
    background-size: cover;
    background-position: center;
    font-family: Georgia, serif;
}


.nav{
    position: absolute;
    top: 20px;
    right: 30px;
}

.nav a{
    text-decoration: none;
    margin-left: 20px;
    padding: 10px 15px;
    background-color: blue;
    color: white;
    font-size: 16px;
}


.admin{
    position: absolute;
    top: 100px;
    text-align: center;
    left: 600px;
    font-size: 60px;
    color:rgb(0, 0, 0);
}


.menu{
    position: relative;
    top: 200px;
    display: flex;
    justify-content: center;
    gap: 10px;
}


.list{
    background-color:brown;
    padding: 15px;
    text-align: center;
    border-radius: 15px;
    font-size: 15px;
}

.list img{
    width: 200px;
    height:200px;
    border-radius: 15px;
}
 

.footer{
    position: fixed;
    bottom: 0;
    width: 100%;
    background-color:black; 
    color: white; 
    text-align: center;
    font-family: 'Times New Roman', Times, serif; 
    padding: 10px;
}
contact.html

<html>
<head>
    <title>Contact</title>
    <link rel="stylesheet" href="contact.css">
</head>
<body>
    <div class="nav">
        <a href="index.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>
    </div>
    <div class="contact">
        <h1>CONTACT</h1>
        <div class="Details">
            <h2><u>VISIT US AT:</u></h2>
            <p>
                <b>CHENNAI CRAVINGS
                <br>
                13,Green Park Avenue
                <br>
                Lakeview Road
                <br>
                Bangalore,India</b>
            </p>

            <h2><u>PHONE:</u></h2>
            <p><b>+91 7397088773</b></p>

            <h2><u>EMAIL ID:</u></h2>
            <p><b>LKrestaurant@gmail.com</b></p>
        </div>
    </div>
    <div class="footer">&copy; LINGESHWARI</div>
</body>
</html>

contact.css

body {
    height: 100vh;
    background-image: url("cont\ img.jpg");
    background-size: cover;
    background-position: center;
    color:darkorange;
}

.nav{
    position: absolute;
    top: 10px;
    right: 300x;
    
    padding: 10px 20px;
    border-radius: 4px;
}

.nav{
    position: absolute;
    top: 10px;
    right: 30px;
}

.nav a{
    text-decoration: none;
    margin-left: 20px;
    padding: 10px 15px;
    background-color: blue;
    color:coral;
    font-size: 20px;
}

.contact {
    padding: 5px 40px;
}

.contact h1 {
    font-size: 50px;
    color: rgb(212, 198, 198);
    margin-bottom: 30px;
    
}

.details h2 {
    font-size: 30px;
    margin-top: 20px;
    color: rgb(236, 213, 213);
}

.details p {
    font-size: 30px;
    line-height: 1;
    margin-top: 2px;
}
.footer{
    background-color: black;
    text-align: center;
    color:aqua;
    padding:10px;
    bottom: 0;
    width: 100%;
    position:fixed;
    
}
```

## OUTPUT:
<img width="1917" height="998" alt="Screenshot 2026-05-26 141229" src="https://github.com/user-attachments/assets/664c1aad-195c-4d3e-9e7c-8e5a755aa573" />

<img width="1904" height="975" alt="Screenshot 2026-05-26 141254" src="https://github.com/user-attachments/assets/7bb1f316-5eab-498d-8ecf-74441f48323d" />

<img width="1914" height="1015" alt="Screenshot 2026-05-26 141317" src="https://github.com/user-attachments/assets/3a88f0bc-1ad4-4928-b747-06461f480736" />

<img width="1640" height="943" alt="Screenshot 2026-05-26 135346" src="https://github.com/user-attachments/assets/dca2d362-9749-431b-b198-a4b1f35e8c1a" />


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
