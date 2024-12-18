# Ex.06 Book Front Cover Page Design
## Date:

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
    <meta name="viewport" content="width=device=width, initial-scale=1.0">
    <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color: rgb(12, 12, 12);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            background-image: url(c:\Users/admin/Desktop/FWAD/bg.jpg);
            background-size: cover;
        }

        .insight{
            color: rgb(16, 15, 15);
        }

        .hrstyle{
            width: 100px;
        }

        .author{
            display: inline;
            position: relative;
            color: rgb(8, 8, 8);
            top: 230px;

            font-family: Verdana, Geneva, Tahoma, sans-serif;
            font-size: medium;
        }

        .booktitle{
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        }

        .id{
            width: 400px;
            position: relative;
            top: 100px;
        }

        .pub{
            font-size: medium;
            position: relative;
            top: 230px;
            left: 315px;
        }

        .ed{
            color:  rgb(17, 17, 16);
            font-size: medium;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            position: relative;
            top: 150px;

        }

        .subtitle{
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            font-size: large;
            position: relative;
            top: 40px;
        }

        .mypic{
            position: relative;
            top: 230px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;

        }
    </style>
    <title>BOOK COVER</title>
</head>
<body>
    <div class="bookpage">
        <div class="insight">INSIGHT</div>
        <div class="hrstyle">
            <hr style="color: rgb(19, 19, 19)">
        </div>
        <div class="booktitle">
         <h1>INTRODUCTION TO ARTIFICIAL INTELLIGENCE</h1>
        </div>
        <div class="subtitle">
            <center>
                BESTSELLER 2024
            </center>
        </div>
        <div class="mypic">
            <img src=c:\Users\admin\Desktop\FWAD\author.jpeg width="125" height="140" alt="">
        </div>
        <div class="id">
            <hr style="color: rgb(18, 17, 17)">
        </div>
        <div class="author">
            <p><b>DARSHINI B</b></p>
        </div>
        <div class="pub">
            
        </div>
        <div class="ed">
            <b>LIMITED EDITION</b>
        </div>
    </div>
</body>

</html>


```


## OUTPUT:
![alt text](<Screenshot 2024-12-18 083813.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
