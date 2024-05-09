# Ex.06 Book Front Cover Page Design
## Date: 2.5.24

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
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <style type="text/css">
      .bookcover {
        width: 400px;
        height: 640px;
        color: rgb(240, 239, 220);
        margin-left: auto;
        margin-right: auto;
        padding: 20px;
        font-family:Georgia, Times, 'Times New Roman', serif;
        background-image: url(web06.jpg);
        background-size: cover;
      }
      .insight {
        color: white;
      }
      .hr {
        width: 100px;
      }
      .h1 {
        font-size: medium;
        font-family: Georgia, Times, 'Times New Roman', serif;
        color: rgb(0, 162, 255);
        text-align: center;
        position: relative;
        top: 30px;
      }
      .h3 {
        font-size: larger;
        font-family: Georgia, Times, 'Times New Roman', serif;
        color: rgb(0, 162, 255);
        text-align: center;
        position: relative;
        top: 10px;
      }
      .p {
        font-size: medium;
        font-family: Georgia, Times, 'Times New Roman', serif;
        position: relative;
        top: 60px;
      }
      .edition {
        font-size: large;
        font-family: Georgia, Times, 'Times New Roman', serif;
        color: rgb(0, 187, 255);
        top: 60px;
        position: relative;
      }
      .photo {
        position: relative;
        top: 100px;
        left: 270px;
        width: 100px;
        height: 70px;
        background-size: cover;
      }
      .hrstyle {
        position: relative;
        width: 400px;
        top: 170px;
      }
      .author {
        font-size: medium;
        font-family: Georgia, Times, 'Times New Roman', serif;
        display: inline;
        position: relative;
        color: whitesmoke;
        top: 165px;
      }
      .publisher {
        font-size: large;
        position: relative;
        top: 135px;
        left: 330px;
      }
    </style>
    <title>Book Front Cover Page</title>
  </head>
  <body>
    <div class="bookcover">
      <div class="insight">SEC INSIGHT</div>
      <div class="hr">
        <hr />
      </div>
      <div class="h1">
        <h1>THE FUTURE TECHNOLOGY</h1>
        <br>
        <h3>"GET INTO THE TECHNOLOGY OF FUTURE"</h3>
      </div>
      <div class="p">
        <p>
            The future of technology promises exciting advancements across AI, AR/VR, IoT, quantum computing, biotech, renewable energy, space exploration, and more, shaping a world of innovation and possibility.











          
        </p>
      </div>
      <div class="photo">
        <img src="web06pic.jpg" width="120" height="150" alt="" />
      </div>
      <div class="hrstyle">
        <hr />
      </div>
      <div class="author">
        <p><b> SANJAY M S </b></p>
      </div>
      <div class="publisher">
        <b> SEC </b>
      </div>
      <div class="edition">
        <b>EXTENDED EDITION</b>
      </div>
    </div>
  </body>
</html>
```
## OUTPUT:
![alt text](<Screenshot (10).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
