# Ex.06 Book Front Cover Page Design
## Date:08/10/2025

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
    <title>Book Cover</title>
    <style>
        body,
        html {
            margin: 0;
            padding: 0;
            height: 100%;
            font-family: 'Georgia', serif;
        }

        .cover {
            position: relative;
            width: 100%;
            height: 100vh;
            background-color: #000;
            overflow: hidden;
        }

        .bg-img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            opacity: 0.7;
            position: absolute;
            top: 0;
            left: 0;
            z-index: 0;
        }

        .content {
            position: relative;
            z-index: 1;
            color: white;
            text-align: center;
            padding-top: 15%;
        }

        .title {
            font-size: 3.5em;
            margin-bottom: 10px;
            color: #fff;
            text-shadow: 2px 2px 8px #000;
        }

        .subtitle {
            font-size: 1.8em;
            margin-bottom: 30px;
            color: #ccc;
        }

        .author-photo {
            position: absolute;
            bottom: 30px;
            right: 40px;
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid rgba(255, 255, 255, 0.8);
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.6);
            z-index: 2;
        }
    </style>
</head>

<body>
    <div class="cover">
        <img src="book cover.jpeg" class="bg-img" alt="Background">
        <img src="photo.jpeg" alt="Author Photo" class="author-photo">
    </div>
</body>

</html>

```

## OUTPUT:
![alt text](<Screenshot 2025-10-08 202750.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
