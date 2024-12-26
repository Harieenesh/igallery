# Ex.08 Design of Interactive Image Gallery
## Date:26/12/2024

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
index.html

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Interactive Photo Gallery</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>
    <h1>Interactive Photo Gallery</h1>
    <div class="container">
      <div class="gallery">
        <img class="preview" src="1.jpeg" onmouseover="upDate(this)" onmouseout="unDo()">
        <img class="preview"  src="2.jpeg" onmouseover="upDate(this)" onmouseout="unDo()">
        <img class="preview"  src="3.jpeg" onmouseover="upDate(this)" onmouseout="unDo()">      
        <img class="preview"  src="4.jpeg" onmouseover="upDate(this)" onmouseout="unDo()">
        <img class="preview"  src="5.jpeg" onmouseover="upDate(this)" onmouseout="unDo()">
      </div>
      <div id="image">"Hover an image below to display here"</div>
    </div>
  </body>
  
<script src="indec.js"></script>

</html>

style.css

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Interactive Photo Gallery</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>
    <h1>Interactive Photo Gallery</h1>
    <div class="container">
      <div class="gallery">
        <img class="preview" src="1.3.jpg" onmouseover="upDate(this)" onmouseout="unDo()">
        <img class="preview"  src="1.2.jpg" onmouseover="upDate(this)" onmouseout="unDo()">
        <img class="preview"  src="1.4.jpg" onmouseover="upDate(this)" onmouseout="unDo()">      
        <img class="preview"  src="1.5.jpg" onmouseover="upDate(this)" onmouseout="unDo()">
        <img class="preview"  src="1.1.jpg" onmouseover="upDate(this)" onmouseout="unDo()">
      </div>
      <div id="image">"Hover an image below to display here"</div>
    </div>
  </body>
  
<script src="indec.js"></script>

</html>

```
## OUTPUT:
![alt text](<Screenshot 2024-12-26 175438.png>)
![alt text](<Screenshot 2024-12-26 175451.png>)
![alt text](<Screenshot 2024-12-26 175503.png>)


## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
