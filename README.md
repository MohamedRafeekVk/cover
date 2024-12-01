# Ex.06 Book Front Cover Page Design
## Date:26/11/2024

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
### HTML:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="./cover.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Web Design Poster</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="poster">
        <div class="header">
            <h5>EXPERT INSIGHT</h5>
            <h5>THIRD EDITION</h5>
            <h2>BOOK COVER</h2>
        </div>
        <div class="content">
            <h1>HTML AND CSS</h1>
            <p>
                HTML (HyperText Markup Language) is the backbone of web pages, used to structure and define the content like text, images, and links.
CSS (Cascading Style Sheets) styles the HTML elements, controlling layout, colors, fonts, and visual effects to enhance the look and feel.
Together, HTML and CSS form the foundation of front-end web development, creating functional and visually appealing websites.


                
            </p>
        </div>
        <div class="edition">
            
        </div>
        <div class="author">
         
            <p>NAME:MOHAMED RAFEEK <br>
                REF.NO:24900640
            </p>
        </div>
        <div class="wave">
            <div class="image"><img src="./Photo For Book Cover.jpg" alt="image"></div>
        </div>
        <div class="footer">
            <p></p>
        </div>
    </div>
</body>
</html>

```
### CSS:
```
body {
    margin: 0;
    font-family: Arial, sans-serif;
    color: white;
    background-color: #ffffff;
}

.poster {
    width: 600px;
    height: 800px;
    margin: 50px auto;
    position: relative;
    background: #1a1a1a;
    border: 2px solid #333;
    padding: 20px;
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.header {
    text-align: left;
    font-size: 18px;
    color: #ff6600;
    margin-bottom: 20px;
}

.content h1 {
    font-size: 32px;
    font-weight: bold;
    line-height: 1.3;
    margin-bottom: 10px;
}

.content p {
    font-size: 16px;
    line-height: 1.5;
    color: #dcdcdc;
}

.edition {
    font-size: 18px;
    font-weight: bold;
    color: #ff6600;
}

.author {
    font-size: 20px;
    font-weight: bold;
    margin-top: auto;
}

.wave {
    position: absolute;
    width: 100%;
    height: 150px;
    bottom: 120px;
    left: 0;
    background: linear-gradient(135deg, #00cc99 50%, transparent 50%);
    clip-path: polygon(0 100%, 0 0, 100% 0, 100% 100%);
    display: flex;
    flex-direction: row-reverse;
}

.footer {
    text-align: right;
    font-size: 24px;
    font-weight: bold;
    color: white;
}

.image {
    width: 120px;
    height: auto;
    padding-right: 20px;
}

img {
    width: 100%;
}
```

## OUTPUT:
![Screenshot (25)](https://github.com/user-attachments/assets/9ff74c76-d887-4418-b43d-56791cb2c152)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
