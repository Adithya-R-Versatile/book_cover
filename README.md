# Ex.06 Book Front Cover Page Design
# Date:05-10-2025
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
```<head>
  <title>Book Cover</title>
</head>
<body style="margin: 0; padding: 0; display: flex; justify-content: center; align-items: center; height: 100vh; background: #696363;">

<div style="width: 350px; height: 500px; background: linear-gradient(135deg, #c5440c, #00b294); color: white; padding: 20px; position: relative; border: 5px solid #fff;">

    <p style="font-size: 14px; font-weight: bold; color: rgb(15, 21, 187);">TIPS</p>
    <hr>
    <h1 style="font-size: 30px; color: #000; font-weight: bold; text-align: center; line-height: 1.4;">HOW TO BECAME<br>MILLIONAIRE</h1>
    <hr>
    <p style="font-size: 20px;color: brown; text-align: center;">Wealth begins with discipline,not luck.</p>
    
    <p style="font-size: 14px; text-align: center;">True Experiences</p>

<div style="display: flex; align-items: center;">
        
        <div style="position:absolute;bottom:100px;left:30px;width: 80px; height: 80px;border:5px solid rgb(11, 3, 3);border-radius:25%;overflow:hidden;">
<img src= {% static "download (5).jpeg" %} style="width: 100%; height: 100%;"></div>
            
    
        <div><p style="position:absolute;bottom:80px;left:56px;font-size: 14px; margin: 0;text-shadow:-1px -1px 0 #000,1px -1px 0 #000,-1px 1px 0 #000,1px 1px 0 #000;">Ratan Tata</p>
        <p style="position:absolute;bottom:65px;left:56px;font-size: 14px; margin: 0;text-shadow:-1px -1px 0 #000,1px -1px 0 #000,-1px 1px 0 #000,1px 1px 0 #000;">1937-2024</p></div>
    
</div>

    <div style="position: absolute; bottom: 20px; Right: 20px; font-size: 14px; font-weight: bold;">
         <img src= {% static "download.jpeg" %} 
       style="width:100px; height:auto; margin-bottom:-12px;">
      <p style="margin: 0; color: red;">Signature</p></div>
    

</div>

</body>
</html>
```
# OUTPUT:![alt text](<Screenshot 2025-10-05 210800.png>)
# RESULT:![alt text](<Screenshot 2025-10-05 210703.png>)
The program for designing book front cover page using HTML and CSS is completed successfully.
