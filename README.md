# Ex.05 Book Front Cover Page Design
## Date: 18-10-2024

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
```html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: beige;
        }

        .book-cover {
            width: 533px;
            height: 800px;
            background-color:black;
            box-shadow: 10px 10px 10px rgb(0, 0, 0);
            margin: 50px auto;
            position: relative;
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        }

        .book-cover .insight {
            position: absolute;
            top: 180px;
            right: 70px;
            font-size: 18px;
            font-weight: bold;
            color: #224115;
            text-shadow: 0px  0px 3px rgb(0, 0, 0);  
            text-decoration: underline;
        }

        .book-cover .title1 {
            position: absolute;
            top: 220px;
            right: 70px;
            text-shadow: 3px  3px 3px rgb(0, 0, 0);    
            text-align: right;
            font-size: 42px;
            font-weight: bold;
            color: #224115;
        }
        .book-cover .subtitle1 {
            position: absolute;
            top: 350px;
            right: 70px;
            text-shadow: 0px  0px 3px rgb(0, 0, 0);
            text-decoration: underline;    
            font-size: 16px;
            font-weight: bold;
            color: #224115;
        }

        .book-cover .author {
            position: absolute;
            bottom: 50px;
            right: 70px;
            font-size: 18px;
            color: #224115;
            text-shadow: 0px  0px 5px rgb(0, 0, 0);
        }

        .book-cover .mypic
        {
            position: absolute;
            top: 600px;
            right: 70px;
            border-radius: 10%;
        }

        .book-cover .image {
            width: 100%;
            height: 100%;
            object-fit: cover;
            position: absolute;
            top:  0;
            left: 0;
        }
    </style>
</head>
<body>
    <div class="book-cover">
        <img src="Images/background-image.jpg" alt="Book Cover Image" class="image">
        <div class="insight"><b>EXPERT INSIGHT</b></div>
        <div class="title1">THE EDITH <br> TIMBERLAND</div>
        <div class="subtitle1">Secrets Beneath the Ancient Forest</div>
        <img src="Images/author-photo.jpg" width="120" height="120" class="mypic">
        <div class="author">Roopak C S</div>
    </div>
</body>
</html>
```

## OUTPUT:
![alt text](Output.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
