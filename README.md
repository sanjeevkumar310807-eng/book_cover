# Ex.06 Book Front Cover Page Design
# Date:19-12-2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
````
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Web Technology Cover Page</title>

    <style>
      body {
        background-color: #ddd;
        font-family: "Times New Roman", serif;
      }

      .page {
        width: 794px; /* A4 width */
        height: 1123px; /* A4 height */
        margin: 20px auto;
        background: white;
        border: 2px solid #999;
        padding: 50px;
        box-sizing: border-box;
      }

      h1 {
        text-align: center;
        color: darkred;
        font-size: 40px;
        margin-bottom: 10px;
      }

      h2 {
        text-align: center;
        font-size: 24px;
        margin-top: 0;
      }

      .photo {
        text-align: center;
        margin: 40px 0;
      }

      .photo img {
        width: 220px;
        height: 280px;
        border: 3px solid darkred;
      }

      .details {
        margin-top: 40px;
        font-size: 22px;
        line-height: 1.8;
      }

      .label {
        font-weight: bold;
      }
    </style>
  </head>

  <body>
    <div class="page">
      <h1>Web Technology</h1>
      <h2>HTML, CSS & Django</h2>

      <div class="photo">
        <img src="pic.jpeg" alt="Student Photo" />
      </div>

      <div class="details">
        <p><span class="label">Name :</span> sanjeev kumar.v</p>
        <p><span class="label">Register No :</span> 25018993</p>
        <p><span class="label">Department :</span> IT</p>
        <p><span class="label">College :</span> Saveetha Engineering College</p>
        <p><span class="label">Academic Year :</span> 2026 - 2027</p>
      </div>
    </div>
  </body>
</html>
````
# OUTPUT:
<img width="1879" height="910" alt="book pic" src="https://github.com/user-attachments/assets/699175b6-8881-4e8e-9349-9cc442bd872d" />

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
