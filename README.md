# Ex.06 Book Front Cover Page Design
## Date: 22/03/2024
## Name : H Vishinu 
## Reg.No : 212223220124
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
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .bookpage {
            width: 400px;
            height: 600px;
            color: rgba(243, 195, 195, 0.938);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(image.png);
            background-size: cover;
        }

        .insight {
            color: rgb(186, 41, 41);
        }

        .hrstyle {
            width: 100px;
        }

        .author {
            display: inline;
            position: relative;
            color: rgb(228, 38, 38);
            top: 240px;
            font-family: Georgia;
            font-size: medium;
        }

        .booktitle {
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
            color: aqua;
        }

        .id {
            width: 400px;
            position: relative;
            top: 250px;
        }

        .pub {
            font-size: medium;
            position: relative;
            top: 204px;
            left: 350px;
            color: blanchedalmond;
        }

        .ed {
            color: rgb(231, 153, 153);
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 150px;
        }

        .subtitle {
            font-family: Tahoma;
            font-size: large;
            position: relative;
            top: 40px;
            color: aqua
        }

        .mypic {
            position: relative;
            top: 120px;
            left: 150px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
    </style>
    <title>Book Cover Page</title>
</head>

<body>
    <div class="bookpage">
        <div class="insight">SEC SERIES</div>
        <div class="hrstyle">
            <hr style="color: rgb(128, 128, 96);">
        </div>
        <div class="booktitle">
            <h1>Fundamentals of Ethical Hacking</h1>
        </div>
        <div class="subtitle">
            The complete guide to Ethical Hacking
        </div>
        <div class="mypic">
            <img src="vishnu.jpg" width="130" height="145" alt="">
        </div>
        <div class="id">
            <hr style="color: rgb(145, 145, 114);">
        </div>
        <div class="author">
            <p><b>H Vishinu</b></p>
        </div>
        <div class="pub">
            SEC
        </div>
        <div class="ed">
            <b>Extended version</b>
        </div>
    </div>
</body>

</html>

```

## OUTPUT:
![Screenshot 2024-05-06 082801](https://github.com/VisHinu24/cover/assets/144244396/b010a238-cb0e-4291-b184-6268a946814d)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
