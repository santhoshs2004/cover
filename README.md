# Ex.06 Book Front Cover Page Design
## Date:

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }

        .bookpage {
            width: 400px;
            height: 600px;
            color: white;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(bg.jpg);
            background-size: cover;
        }

        .insight {
            color: white;
        }

        .hrstyle {
            width: 100px;
        }

        .author {
            display: inline;
            position: relative;
            color: rgb(228, 222, 145)
            top: 190px;
            font-family: Georgia;
            font-size: medium;
        }

        .booktitle {
            font-family: Arial, Helvetica, sans-serif;
            font-size: 19px;
            text-align: center;
            position: relative;
            top: 30px;
        }

        .id {
            width: 400px;
            position: relative;
            top: 180px;
        }

        .pub {
            font-size: medium;
            position: relative;
            top: 155px;
            left: 330px;
        }

        .ed {
            color: white;
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 85px;
        }

        .subtitle {
            font-family: Tahoma;
            font-size: large;
            position: relative;
            top: 40px;
        }

        .mypic {
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
    </style>
    <title>Book Cover Page</title>
</head>

<body>
    <div class="bookpage">
        <div class="insight">EXPERT INSIGHT</div>
        <div class="hrstyle">
            <hr style="color: white;">
        </div>
        <div class="booktitle">
            <h1>COMPUTER SYSTEM AND NETWORK SECURITY</h1>
        </div>
        <div class="subtitle">METHODOLOGY TO MAINTAIN NETWORK SECURITY</div>
        <div class="mypic"><img src="image 1.jpeg" width="130" height="145" alt=""></div>
        <div class="id">
            <hr style="color: white;">
        </div>
        <div class="author">
            <p><b>BY RIZWAN T</b></p>
        </div>
        <div class="pub">OPEN >>></div>
        <div class="ed"><b>Special Edition</b></div>
    </div>
</bodY>

</html>
```


## OUTPUT:

![image](https://github.com/rizwanrayyan/cover/assets/121215820/0686f682-510b-4970-8edf-28d7237b5a8e)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
