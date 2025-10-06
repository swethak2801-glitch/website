# Ex.07 Restaurant Website
# Date:6.10.25
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```


    <head>
        <title>NILA RESTAURANT</title>
    
    </head>
    <style>
        body{
            background-size: cover;
            background-position: center;
        }
        .nav-list{
            position: absolute;
            top: 30px;
            left: 80%;
            transform:  translatex(10%);
        }
        .nav-list a{
            display: inline blocks;
            margin: 0 10px;
            font-family:italic;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            color: black;
        }
        .nav-list a:hover{
            color: red;
        }
    </style>
        <div class="nav-list">
        
        <a href="rest.html">Home</a>
        <a href="contact.html">contact</a>
        <a href="menu.html">menu</a>
        <a href="admin.html">Administration</a>

        </div>
    <body style="color:black;">
        <center>
       
        </center>
        <center>
            <h1 style= "color:black; font-size: 50px;">THE NILA RESTAURANT</h1>
    <table> 
        <center>
        <tr>
            <td><img src="biriyani.jpg.png"" style="width: 300px; height: 250px;"></td>
            <td><img src="Screenshot 2025-10-05 130315.png" style="width:300px; height: 250px;"></td>
            <td><img src="chicken rice.png" style="width:300px; height: 250px;"></td>
            <td><img src="parota.png" style="width:300px; height: 250px;"></td>
            <td><img src="VAANGI.png" style="width:300px; height: 250px;"></td>
        </tr>
        </center>
        <tr>
            <td><h3 style="color:black;"><center>BIRIYANI</center></h3></td>
            <td><h3 style="color:black;"><center>CHICKEN KABAB </center></h3></td>
            <td><h3 style="color:black;"><center>CHICKEN RICE</center></h3></td>
            <td><h3 style="color:black;"><center>PAROTA</center></h3></td>
            <td><h3 style="color:black;"><center>VAANGI BAATH</center></h3></td>
        </tr>
    </table>
    <h2>About us:
        <h2><center></center></h2>
    </h2>
        <p style="font-family: 'Times New Roman',Times, serif";><center>At Gourmet Delight, we bring you a fusion of flavors from around the world, crafted with love and the freshest ingredients. 
            Our restaurant offers a warm and inviting atmosphere, perfect for family gatherings, romantic dinners, or casual outings with friends. 
            Indulge in our chef's specialties and let us take you on a culinary journey you will never forget. Your satisfaction is our priority!

        </p> 
        <hr>
        <tr>
            <td><h4 style="font-size: larger;"><center>SAVOUR THE FLAVOURS:A CULINARY PARADAISE AWAITS</center></h4></td>
        </tr>
        <footer allign="centre" id="copy erite"
            Designed and developed by Swetha & copy 2025
        </footer>
    </body>        
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>THE NILA - Administration</title>

    
    <style>
        body {
            margin: 0;
            font-family: Georgia, 'Times New Roman', Times, serif;
            line-height: 1.6;
            color: #333;
            background-color: #f3f4f6;
            box-sizing: border-box;
        }

        *, *::before, *::after {
            box-sizing: inherit;
        }

        header {
            background: #e0f7fa;
            color: #00796b;
            padding: 15px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 1.8rem;
            font-family: 'Playfair Display', serif;
        }

        header nav a {
            text-decoration: none;
            color: #00796b;
            font-weight: 500;
            margin: 0 15px;
            transition: color 0.3s ease;
            font-size: 1rem;
        }

        header nav a:hover {
            color: #004d40;
        }

        .admin-container {
            padding: 40px 20px;
            background: #d5a4c0;
            text-align: center;
        }

        .admin-container h1 {
            font-size: 2.5rem;
            color: #0077cc;
            margin-bottom: 20px;
            font-family: 'Playfair Display', serif;
        }

        .admin-items {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
        }

        .admin-item {
            background: #f0f4c3;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 280px;
            overflow: hidden;
            transition: transform 0.3s ease;
            text-align: left;
        }

        .admin-item img {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }

        .admin-item:hover {
            transform: scale(1.05);
        }

        .admin-details {
            padding: 15px;
        }

        .admin-details h3 {
            font-size: 1.4rem;
            color: #333;
            margin-bottom: 8px;
        }

        .admin-details p {
            font-size: 1rem;
            color: #555;
            margin-bottom: 10px;
        }

        footer {
            background: #f9f9f9;
            color: #555;
            text-align: center;
            padding: 15px 0;
            font-size: 0.9rem;
        }

        footer a {
            color: #0077cc;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: #005fa3;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 1.5rem;
            }

            .admin-items {
                flex-direction: column;
                gap: 20px;
            }

            .admin-item {
                width: 100%;
            }

            header nav a {
                font-size: 0.9rem;
                margin: 0 5px;
            }
        }
    </style>
</head>
<body>                
<header>
<div class="admin-container">
    <h1>OUR BACKBONES</h1>
    <div class="admin-items">
        <div class="admin-item">
            <img src="nelsonn.png" alt="CEO">
            <div class="admin-details">
                <h3>NELSON</h3>
                <p>CEO of THE NILA RESTAURANT</p>
            </div>
        </div>

        <div class="admin-item">
            <img src="image copy.png" alt="Manager">
            <div class="admin-details">
                <h3>SINDHU</h3>
                <p>Manager of THE NILA RESTAURANT</p>
            </div>
        </div>

        <div class="admin-item">
            <img src="image.png" alt="Master Chef">
            <div class="admin-details">
                <h3>BHAT</h3>
                <p>Master Chef of THE NILA RESTAURANT</p>
            </div>
        </div>

        <div class="admin-item">
            <img src="MANAGER.png" alt="Assistant Managing Director">
            <div class="admin-details">
                <h3>STOCK</h3>
                <p>Assistant Managing Director of THE NILA RESTAURANT</p>
            </div>
        </div>
    </div>
</div>



</body>
</html>
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contact</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Georgia, serif;
            font-size: 23px;
            font-weight: bold;
            color: blue;
            background-image: url("bg.pg.jpg");
            background-size: cover;
            background-position: center;
        }

        .contact-container {
            max-width: 600px;
            margin: 200px auto;
            background-color: rgba(255, 255, 255, 0.8);
            padding: 30px;
            border-radius: 10px;
            text-align: center;
        }

        h1, h4, p {
            color: black;
        }
    </style>
</head>
<body>
    <div class="contact-container">
        <section id="contact">
            <h1>Contact</h1>
            <h4>+91 9986842532<br>Nila.restaurant@gmail.com</h4>
            <p>
                3/32, Anna Nagar, Thiruvannamalai, 605802<br><br>
                Contact us to place your order.<br><br>
                <hr>
                SAVOUR THE FLAVOUR
            </p>
        </section>
    </div>
</body>
</html>
```
# OUTPUT:
<img width="1900" height="848" alt="Screenshot 2025-10-06 220039" src="https://github.com/user-attachments/assets/cc1a16ef-bc1c-4c48-9c7b-87b9cb4a7ffa" />
<img width="1872" height="867" alt="Screenshot 2025-10-06 213744" src="https://github.com/user-attachments/assets/b0ef92d8-f810-470c-9344-b36d7988ace5" />
<img width="1413" height="380" alt="Screenshot 2025-10-06 213810" src="https://github.com/user-attachments/assets/f68f7810-9a8b-4f6d-9a84-e3ebdda2bf54" />



# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
