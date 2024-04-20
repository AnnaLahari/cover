# Ex.06 Book Front Cover Page Design
## Date:20-4-2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<html>
<head>
    <title>CSE</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image: url(back.png);
            background-size: cover;
        }
            
        
        .insight{
            color:red;
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:crimson(255, 255, 255);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:red;
            font-family: Roquen;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            color:red;
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:red;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        
        }
        .subtitle{
            color:red;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
            
            </div>
            <div class="hrstyle">
                <hr style="color:black">
            </div>
            <div class="booktitle">
                <h1>FUTURE TECHNOLOGIES OF AI</h1></div>
            <div class="subtitle">
                 books for beginners
            </div>
            <div class="subtitle">
                 Top seller of 2024
            </div>

            <div class="mypic">
                <img src="img.jpg" width="120" height="100" >
            </div>
            <div class="id">
                <hr style="color:black">
            </div>
            <div class="author">
               <p><b>A.LAHARI(212223230111)</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>SPECIAL EDITION(LIMITED STOCK)</b>
            </div>
        </div>
        </body>
</html>
```
## OUTPUT:

![Screenshot 2024-04-20 120601](https://github.com/AnnaLahari/cover/assets/149365425/f85e5a6e-1eb7-4111-8930-6bd3cb6a0fb4)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
