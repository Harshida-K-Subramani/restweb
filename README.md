# Ex.07 Restaurant Website
## Date: 11-05-2025

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
resturant.html
```
<html>
    <head>
        <title>FOODIE</title>
    </head>
    <body>
        <style>
            .bg{
                position: relative;
                text-align: justify;
           }
           .title{
                position: relative;
                text-align: center;
                bottom: 660px;
                color:rgb(222, 80, 168);
                font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
                font-style: italic;
                font-size:larger;
                font-weight: 1000px;
            }
            .logo{
                position: relative;
                align:center;
                bottom: 400px;
                width: 90px;
                height: 80px;
            }
            .text{
                position: relative;
                text-align: justify;
                bottom: 590px;
                color:rgb(59, 26, 169);
                font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
                font-style: italic;
                font-size:larger;
                font-weight: 1000px;
                text-align:center;
            }
            .chicken{
                position: relative;
                left: 200px;
                bottom: 550px;
                width: 90px;
                height: 80px;
            }
            .text1{
                position: relative;
                text-align: justify;
                bottom: 500px;
                color:rgb(53, 228, 234);
                font-family: 'Times New Roman', Times, serif;
                font-style: italic;
                left:200px;
                font-size:larger;
                font-weight: 1000px;
            }
            .mutton{
                position: relative;
                left: 500px;
                bottom: 710px;
                width: 90px;
                height: 80px;
            }
            .text2{
                position: relative;
                text-align: justify;
                bottom: 660px;
                color:rgb(53, 228, 234);
                font-family: 'Times New Roman', Times, serif;
                font-style: italic;
                left:510px;
                font-size:larger;
                font-weight: 1000px;
            }
            .fish{
                position: relative;
                left: 800px;
                bottom: 870px;
                width: 90px;
                height: 80px;
            }
            .text3{
                position: relative;
                text-align: justify;
                bottom: 820px;
                color:rgb(53, 228, 234);
                font-family: 'Times New Roman', Times, serif;
                font-style: italic;
                left:830px;
                font-size:larger;
                font-weight: 1000px;
            }
            .veg{
                position: relative;
                left: 1122px;
                bottom: 1027px;
                width: 90px;
                height: 80px;
            }
            .text4{
                position: relative;
                text-align: justify;
                bottom: 984px;
                color:rgb(53, 228, 234);
                font-family: 'Times New Roman', Times, serif;
                font-style:italic;
                left:1158px;
                font-size:larger;
                font-weight: 1000px;
            }
            .contact{
                position: relative;
                text-align: justify;
                bottom: 1550px;
                color:rgb(53, 228, 234);
                font-family: Georgia, 'Times New Roman', Times, serif;
                font-style: italic;
                left:1100px;
                font-size:larger;
                font-weight: 1000px;
            }
            .id{
                position: relative;
                text-align: justify;
                bottom: 1580px;
                color:rgb(53, 228, 234);
                font-family: Georgia, 'Times New Roman', Times, serif;
                font-style: italic;
                left:1100px;
                font-size:larger;
                font-weight: 1000px;
            }

        </style>
        <div class="bg">
            <img src="bg.jpg" height="700" width="2000">
            <div class="title">
                <h1>FOODIE RESTURANT</h1>
                <img src="logo.jpeg" height="100" width="150">
            </div>
            <div class="text"><h1>MENU</h1></div>
            <div class="chicken">
                <img src="chicken.avif" height="150" width="150">   
            </div>
            <div class="text1"><h2><a href="chicken.html">CHICKEN</h2></div>
            <div class="mutton">
                <img src="mutton.jpg" height="143" width="145">
            </div>
            <div class="text2"><h2 ><a href="mutton.html">MUTTON</h2></a></div>
            <div class="fish">
                <img src="fish.jpg" height="140" width="150">
            </div>
            <div class="text3"><h2 ><a href="fish.html">FISH</h2></a></div>
            <div class="veg">
                <img src="veg.webp" height="147" width="150">
            </div>
            <div class="text4"><h2 ><a href="veg.html">VEG</h2></a></div>
            <div class="contact">
                <h2>CONTACT US BY</h2>
            </div>
            <div class="id">
                <h5><a href="contact.html">harshida@foodieresturant.com</h5></a>
            </div>
        </div>
    </body>
</html>
```
chicken.html
```
<html>
    <head>
        <title>CHICKEN</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="red"><b><br>CHICKEN VARITIES</b></font>
        </h1>
        <br>
        <hr size="3" color="black">
        <br>
        <img src="chicken briyani.jpg" alt="" height="300" width="260" >
        <img src="chicken lollipop.jpeg" alt="" height="300" width="270">
        <img src="chittinad chicken curry.jpg" alt="" height="300" width="290">
        <img src="grilled chicken.jpg" alt="" height="300" width="290">
        <img src="pepper chicken.jpg" alt="" height="300" width="250">
        <h2>**CHICKEN BRIYANI___CHICKEN LOLLIPOP___CHITTINAD CHICKEN____GRILLED CHICKEN____PEPPER CHICKEN**</h2>
    </body>
</html>
```
mutton.html
```
<html>
    <head>
        <title>MUTTON</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="red"><b><br>MUTTON VARITIES</b></font>
        </h1>
        <br>
        <hr size="3" color="black">
        <br>
        <img src="mutton briyani.jpg" alt="" height="300" width="260" >
        <img src="mutton curry.jpg" alt="" height="300" width="270">
        <img src="mutton korma.cms" alt="" height="300" width="290">
        <img src="mutton pepper fry.jpg" alt="" height="300" width="290">
        <img src="mutton sukha.png" alt="" height="300" width="250">
        <h2>**MUTTON BRIYANI____MUTTON CURRY_______MUTTON KORMA_____MUTTON PEPPER FRY____MUTTON SUKHA**</h2>
    </body>
</html>
```
Fish.html
```
<html>
    <head>
        <title>FISH</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="red"><b><br>FISH VARITIES</b></font>
        </h1>
        <br>
        <hr size="3" color="black">
        <br>
        <img src="fish curry.jpg" alt="" height="300" width="260" >
        <img src="grilled fish.jpg" alt="" height="300" width="270">
        <img src="fish fry.jpg" alt="" height="300" width="290">
        <img src="chettinad fish gravy.jpeg" alt="" height="300" width="290">
        <img src="baked fish.jpeg" alt="" height="300" width="250">
        <h2>*****FISH CURRY_________GRILLED FISH_____________FISH FRY________CHITTINAD GRAVY________BAKED FISH*****</h2>
    </body>
</html>
```
Veg.html
```
<html>
    <head>
        <title>VEG</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="red"><b><br>VEG VARITIES</b></font>
        </h1>
        <br>
        <hr size="3" color="black">
        <br>
        <img src="veg meals.jpg" alt="" height="300" width="260" >
        <img src="veg gravy.jpg" alt="" height="300" width="270">
        <img src="veg cutlet.jpg" alt="" height="300" width="290">
        <img src="gobi 65.jpg" alt="" height="300" width="290">
        <img src="garlic mushroom.jpg" alt="" height="300" width="250">
        <h2>***VEG MEALS__________VEG GRAVY____________VEG CUTLET______________GOBI 65__________GARLIC MUSHROOM**</h2>
    </body>
</html>
```
contact.html
```
<html>
    <head>
        <title>contact</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="red"><b><br>CONTACT DETAILS</b></font>
        </h1>
        <br>
        <hr size="3" color="black">
        <br>
        <center>
            <h2>
                NAME:  FOODIE REATURANT<br><br>
                BRANCH AT: CHENNAI<br><br>
                ADDRESS : 12/9 ABC STREET,ECR ROAD,CHENNAI,600041.<br><br>
                ORDER AT : harshi@foodieresturant@gmail.com<br><br>
                PH NUMBER : +91 8345756315

            </h2>
        </center>
    </body>
</html>
```

## OUTPUT:

![alt text](exp7op1.png)
![alt text](exp7op2.png)
![alt text](exp7op3.png)
![alt text](exp7op4.png)
![alt text](exp7op5.png)
![alt text](exp7op6.png)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
