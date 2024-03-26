# Ex.06 Book Front Cover Page Design
## Date: 26-02-24

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
        <title>
            Front cover page
        </title>
        <style>
            .bookpage{
                height:680px;
                width:600px;
                margin-left:35%;
                background-image: url(bg5.png);
                padding:10px;
                background-size: cover;
            }
            .hr1{
                width:200px

            }
            .booktitle{
                margin-top: 30px;
                color:white;
                padding:5px;
                font-size: xx-large;
            }
            .subtitle{
                color:white;
                font-size: large;
            }
            
            .mypic{
                position: relative;
                top:90px;
                left:470px;
                height: 100px;
                width: 70px;
            }
            .hr2{
                padding-top: 130px;
            
            }
            *{
                color: white;
            }
            .ed{
                position:relative;
                top: 80px;
            }
            .author{
                font-family: 'Trebuchet MS';
                font-size: large;
            }
            .pb{
                position: relative;
                left:420px;
                top:-50px;
                font-size: x-large;
            }
        </style>
        <body>
            <div class="bookpage">
            <div style="color:white">INSIGHT </div>
            <div class="hr1"><hr ></div>
            <div class="booktitle"><h1>Beginning CSS Web Development</h1></div>
            <div class="subtitle">From Novice to Professional<br>Packed with essential practical techniques---</div>
            <div class="mypic"><img src="img1.png.jpg" height="140px" ></div>
            <div class="ed">SPECIAL EDITION</div>
            <div class="hr2"><hr ></div>
            <div class="author"> REVATHI K</div>
            <div class="pb"> <h2>SEC</h2></div>
        </div>
        </body>
    </head>
</html>


```

## OUTPUT:
![Alt text](<Screenshot (16).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
