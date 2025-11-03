# Ex.06 Book Front Cover Page Design
## Date:03.11.25

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

<head>
  
    <style>
        .bookpage {
            width: 550px;
            height: 650px;
            margin-left: auto;
            margin-right: auto;
            
            padding: 20px;
            font-family: 'Adobe Garamond', serif;
            background-image:url("Screenshot 2025-11-01 142914.png"); 
            
            background-position: center;
            color: #F4E1A6; 
        }

        .insight {
            color: inherit; 
            font-weight: bold;
            font-size: medium;
            font-family: 'Adobe Garamond', serif;
        }

        .hrstyle {
            width: 120px;
            height: 3px;
            background-color: red;
            border: none;
            
            
        }

        .author {
            display: inline;
            position: relative;
            color: inherit; 
            top: 170px;
            font-family: 'Adobe Garamond', serif;
            font-size: large;
            font-weight: bold;
        }

        .booktitle {
          font-family: 'Adobe Garamond', serif;
          font-size: xx-large;
          text-align: center;
          position: relative;
          top: -50px; 
          font-weight: bold;
          letter-spacing: 2px;
          color: inherit;
        }

        .id {
            width: 104%;
            position: relative;
            top: 180px;
            height: 3px;
            background-color: yellow;
        }

        .pub {
            font-size: medium;
            position: relative;
            top: 130px;
            left: 400px;
            color: inherit;
            font-family: 'Adobe Garamond', serif;
        }

        .ed {
            color: inherit;
            font-size: medium;
            font-family: 'Adobe Garamond', serif;
            position: relative;
            top: 70px;
        }

        .subtitle {
            font-family: 'Adobe Garamond', serif;
            font-size: larger;
            font-weight: bold;
            position: relative;
            top: -90px;
            color: #FFFFFF;
            text-align: center;
        }

        .authorpic {
            position: relative;
            top: 110px;
            left: 370px;
            width: 170px;
            height: 100px;
            background-size: cover;
        }
.author,.pub,.ed{
  color: #EAEAEA;
}


    </style>
    <title>Book Cover Page</title>
</head>
<body>
  
    <div class="bookpage">
      
        <div class="insight">
           Dr.APJ Abdul Kalam
        </div>
        <div class="hrstyle">
            <hr>
        </div>
        <div class="booktitle">
             <h1>DREAM THINK ACT</h1>
        </div>
        <div class="subtitle">
             Dream Think Act
        </div>
        <div class="authorpic">
            <img src="authorpic.jpg" width="160" height="160">
        </div>
        <div class="id">
            <hr>
        </div>
        <div class="author">
            <p><b>Dr.APJ Abdul Kalam</b></p>
        </div> 
        <div class="pub">
           Bloomsbury Publishing
        </div>
        <div class="ed">
            <b>Extended Edition</b>
        </div>
    </div>
</body>
</html>
```
## OUTPUT:

<img width="725" height="843" alt="image" src="https://github.com/user-attachments/assets/887c5b74-945b-4fed-abde-2359eb92c451" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
