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
'''
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>HTML & CSS Introduction</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <style>
        body {
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
            background-color: #111;
        }
        
        .book {
            width: 320px;
            height: 480px;
            position: relative;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
        }
        
        .diagonal-split {
            position: absolute;
            width: 100%;
            height: 100%;
            background: linear-gradient(to bottom right, #ffdb15 0%, #ffdb15 50%, #000 50%, #000 100%);
        }
        
        .content {
            position: relative;
            width: 100%;
            height: 100%;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 40px;
            box-sizing: border-box; /* Added back for proper padding */
        }
        
        .title {
            font-family: 'Playfair Display', serif;
            font-size: 2.2rem;
            font-weight: 700;
            margin-bottom: 1.5rem;
            color: white;
            line-height: 1.2;
        }
        
        .title span {
            display: block;
            font-size: 1.8rem;
            margin-top: 0.5rem;
        }
        
        .subtitle {
            font-family: 'Playfair Display', serif;
            font-size: 1.1rem;
            font-style: italic;
            color: white;
            position: relative;
            padding-top: 1.5rem;
        }
        
        .subtitle:before {
            content: "";
            position: absolute;
            top: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 2px;
            background-color: white;
        }
        
        .ampersand {
            font-style: normal;
            font-size: 2.5rem;
        }
        
        .credits {
            position: absolute;
            bottom: 20px;
            right: 20px;
            font-family: 'Playfair Display', serif;
            color: white;
            font-size: 0.9rem;
            text-align: right; /* Added back for credit alignment */
            line-height: 1.4; /* Added back for spacing between lines */
        }
    </style>
</head>
<body>
    <div class="book">
        <div class="diagonal-split"></div>
        <div class="content">
            <div class="title">
                Introduction to
                <span>HTML <span class="ampersand">&</span> CSS</span>
            </div>
            <div class="subtitle">Web Development Essentials</div>
            <div class="credits">
                Shailesh Kumar G<br>
                212224220093
            </div>
        </div>
    </div>
</body>
</html>
'''

## OUTPUT:
![alt text](Screenshot_2025-04-27_16-46-25.jpg)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
