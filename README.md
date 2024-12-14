# Ex.07 Restaurant Website
## Date:14/12/2024

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
administation.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administraion</title>
    <style>
        body
        {
            background-color: rgba(255, 60, 0, 0.733);
        }
        #container
        {
            background-color: whitesmoke;
            display: flex;
            border: 5px solid aquamarine;
            height: 500px;
            width: auto;
            justify-content: space-evenly;
            border-radius: 100px;
        }
        #main
        {
            border: 1px solid black;
        }
        .box
        {
            position: relative;
            display: inline-block;
            top: 150px;
            height: 200px;
            width: 200px;
            border: 2px solid black;
            background-color: pink;
            border-radius: 50%;
        }
        #head
        {
            text-align: center;
            font-size: 40px;
            font-family: 'Times New Roman', Times, serif;
            font-weight: 700;
            background-size:cover ;
        }
        #name
        {
            justify-content: space-evenly;
        }
        #n1
        {
            position: absolute;
            bottom: 250px;
            left: 135px;
            font-weight: 600;
            font-size: large;
            font-style: oblique;
        }
        #n2
        {
            position: absolute;
            bottom: 250px;
            left: 450px;
            font-weight: 600;
            font-size: large;
            font-style: oblique;
        }
        #n3
        {
            position: absolute;
            bottom: 250px;
            left: 725px;
            font-weight: 600;
            font-size: large;
            font-style: oblique;
        }
        #n4
        {
            position: absolute;
            bottom: 250px;
            left: 950px;
            font-weight: 600;
            font-size: large;
            font-style: oblique;
        }
        #n5
        {
            position: absolute;
            bottom: 250px;
            left: 1300px;
            font-weight: 600;
            font-size: large;
            font-style: oblique;
        }
    </style>
    
</head>
<body>  
    <div align="center" id="head">Head Chef</div>
    <div id="container">

            <div ><img src="dhamu.jpg" class="box"></div>
            <div ><img src="kapoor.jpeg" alt="" class="box"></div>
            <div ><img src="karima.jpeg" alt="" class="box"></div>
            <div ><img src="madhampatty.jpeg" alt="" class="box"></div>
            <div ><img src="venkatesh.jpeg" alt="" class="box"></div>

    </div>
    <p id="n1">K. Damodharan </p> 
        <p id="n2">Kapoor</p>
         <p id="n3">Karima</p>
        <p id="n4">Madhampatty  Rangarajr</p>  
        <p id="n5">Venkatesh</p>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        .image-container{
            width:40%;
            height: 70%;
        }
        .centered-text{
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%,-50%);
            font-size: x-large;
            font-weight: 500;
            background-color:antiquewhite;
          }
        
    </style>
    <body>
        <div class="image-container">
            <img src="harsharestaurtant.jpg" width="2000">
        </div>
    <div class="centered-text">
     <center>
   <h1> CONTACT US </h1>
</center>
    <b>phone no: 9789752716| email -"harshafoods@gamil.com"|<br>
        harsha foods- hotels Pvt Ltd.,<br>
        no,11,VG streets,<br>
        poonthamalli , chennai 604206</b>
    </div>
    </body> 
</head>

Food.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HARSHA FOODS</title>
    <style>
        pre{
            padding: 15px;
            font-size: large;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            
        }
       #order
        {
                display: inline;
                margin-left: 10px;
                color: blueviolet;
        }
        #h1
        {
            text-align: center;
            font-style: oblique;
            margin-top: 10px;
            padding: 25px;
            position: relative;
            top: 50px;
            left: 0px;
            background-color: rgb(185, 255, 232);
        }
        body
        {
            background-color: rgba(238, 207, 212,0.3);
        }
    </style>
</head>
<body >
    
    <h1 id="h1">About Us - Harsha Foods</h1>
    <pre>
        

<b>Welcome to Harsha Foods – !</b>

At Harsha Foods, we are committed to offering a dining experience that celebrates the bounty. Situated along the coast, our restaurant specializes in serving the freshest, highest quality food, sourced directly from local men and sustainable suppliers.

Our journey started with a simple vision: to create a place where people can enjoy a variety of delicious food dishes made with love, care, and the finest ingredients. Whether you're a lifelong food lover or trying it for the first time, we promise to deliver an unforgettable meal every time.

<b>What Makes Us Special?</b>
A specialty food is a food that is typically considered as a "unique and high-value food item made in small quantities from high-quality ingredients". Consumers typically pay higher prices for specialty foods, and may perceive them as having various benefits compared to non-specialty foods.


A Menu Full of Flavor
From our signature dishes creations, each dish is crafted to highlight the natural flavors of the Indian spices. We offer something for everyone, whether you prefer grilled, fried, or steamed food, or something with a bit of flair.

A Warm, Welcoming Atmosphere
Our restaurant is designed with comfort in mind. Whether you're here for a casual meal with family or a special night out, we strive to create an inviting space where you can relax and enjoy your meal in good company.

<b>Why Choose Harsha Foods?</b>

Thank you for choosing Harsha foods – we look forward to serving you fresh dishes that will delight your taste buds!


    </pre>

</body>
</html>

order_now.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>order now</title>
    <style>
        body{
            background-color:crimson;
        }
        #body
        {
            border: 5px solid black;
           color: black;
           background-color:wheat;
            border-radius: 25px;
            height: 600px;
        }
         img
        {
                margin-top: 100px;
                height: 200px;
                width: auto;
                margin-left: 25px;

        } 

    </style>
</head>
<body>
    <div id="body">
    <h1 align="center">Order Foods Here</h1>
    <div>
        <table>
            <tr>
        <td><img src="fish fry.jpg" alt=""></td>
    
        <td><img src="shrimp fry.jpeg" alt=""></td>
        <td><img src="Garlic-Chicken.jpg" alt=""></td>
        <td><img src="tandoori.jpeg" alt=""></td>
        <td><img src="paneer tikka.jpeg" alt=""></td>
        <td><img src="fried chicken.jpg" alt=""></td>
 </tr>
    </table>

        <p>- It's time to enjoy the Finer things in Life</p>
    </div>
    </div>
</body>
</html>

web.css

*{
    margin: 0px;
    padding: 0px;
}

#template
{
    align-items: center;
    width: 100%;
    object-fit: cover;
    /* height: 800px; */
}
#tag
{
    position: absolute;
    top:40px;
    left:375px;
    text-decoration: none;
    color: cyan;
    font-weight: 400;
    color:antiquewhite;
    text-transform: capitalize;
    font-size: 40px;
    
}
#order
{
    position: absolute;
    top:50px;
    left: 725px;
    text-decoration: none;
    color:antiquewhite;
    font-weight: 400;
    font-size: 30px;
}
#contact
{
    position: absolute;
    top:50px;
    left: 950px;
    text-decoration: none;
    color: antiquewhite;
    font-weight: 400;
    font-size: 30px; 
}
#offers
{
    position: absolute;
    top:50px;
    left: 1200px;
    text-decoration: none;
    color: antiquewhite;
    font-weight: 400;
    font-size: 30px;   
}
#copywrite
{
    background-color: rgb(255, 115, 0);
    color:black;
    font-size: large;
}

web.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Food app</title>
    <link rel="stylesheet" href="web.css">
</head>
<body>
    <div align="center" id="template">

        <img src="rest background.jpeg" height="700" width="1500">
        <a href="Food.html" id="tag" >HARSHA FOODS</a>
        <a href="order_now.html" id="order">ORDER NOW </a>
        <a href="contact.html" id="contact">CONTACT US</a>
        <a href="administration.html" id="offers">ADMINISTRATION</a>

    </div>
    <footer align="center " id="copywrite"> 
        Designed and Developed by Harshadharshini &copy 2024
    </footer>
</body>
</html>



```


## OUTPUT:
![alt text](<Screenshot (19).png>)
![alt text](<Screenshot (18).png>)
![alt text](<Screenshot (20).png>)
![alt text](<Screenshot (16).png>)
![alt text](<Screenshot (21).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
