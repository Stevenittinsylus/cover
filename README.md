# Ex.06 Book Front Cover Page Design
## Date:21/12/24

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

<!DOCTYPE html>
<html>

<head>
    <title>Book Cover Design</title>
    <style> 
        .wrapper {
            background-color:#000000;
            height:100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .bookpage{
            width: 400px;
            height: 600px;
            color: black;
            padding: 30px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image:url(cov1.jpg) ;
            background-position: center;
            background-size: cover;
        }
            
        
        .insight{
            color: rgb(236, 243, 250);
        
        }
        
        
        .hrstyle{
            width: 160px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(236, 245, 245);
            top: 270px;
            font-family: Georgia;
            font-size: medium;
            padding-bottom: 20px;
        }
        .booktitle{
            color: rgb(251, 50, 0);
            font-family: 'Courier New', Courier, monospace, bold;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width: 400px;
            position: relative;
            top: 280px;
            
        }
        .pub{
            color: rgb(12, 14, 14);
            font-size: medium;
            position: relative;
            top: 235px;
            left: 330px;
        }
        .ed{
            color: rgb(9, 9, 9);
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 190px;
        
        }
        .subtitle{
            color:gold;
            font-family: unicorn;
            font-size: larger;
            position: relative;
            top: 15px; 

        }
        .subtitle2{
            color: rgb(188, 204, 255);
            font-family: Arial, Helvetica, sans-serif;
            font-size: small;
            position: relative;
            top: 250px;
        }
        .mypic{
            position: relative;
            top: 250px;
            left: 300px;
            width: 90px;
            height: 80px;
            background-size: contain;
        }
    </style>
</head>
<body>
    <div class="wrapper">
        <div class="bookpage">
            <div class="insight">
                <b>C++</b>
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1><b>INTRODUCTION TO C++</b></h1></div>
            <div class="subtitle">
                 <b> FOR BEGINNERS </b> 
            <div class="subtitle2">
                <b>>> Basics</b><br>
                <b>>> OOPs</b><br>
                <b>>> Class and Objects</b><br>
            </div>     
            </div>
            <div class="mypic">
                <img src="pic.jpg" width="100" height="100" >
            </div>
            <div class="id">
                <hr style="color:rgb(208, 205, 255)">
            </div>
            <div class="author">
               <p><b>STEVE NITTIN SYLUS(24001421)</b></p>
            </div>
            <div class="pub">
                <p style="color: beige;">SEC 28'</p>
                
            </div>
        </div>
    </div>
</body>
</html>
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/41c14129-4e74-49bd-bd58-a864c621fd6d)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
