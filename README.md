# Ex08 Event Registration Web Application
# Date: 16-12-2025
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
```
home.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-plus">
      <div class="group">
        <img class="MUSIC" src="img/MUSIC-1.png" />
        <div class="rectangle"></div>
        <div class="text-wrapper">LOGIN</div>
        <div class="div"></div>
        <div class="text-wrapper-2">REGISTER</div>
        <div class="text-wrapper-3">MUSIC CONTEST</div>
      </div>
    </div>
  </body>
</html>

style.css

.box {
  display: flex;
  align-items: flex-start;
  min-width: 430px;
}

.box .iphone-plus {
  position: fixed;
  width: 430px;
  height: 932px;
  z-index: 1;
}

category.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-plus">
      <div class="group">
        <div class="frame">
          <div class="div">
            <img class="MUSIC" src="img/MUSIC-1.png" />
            <div class="text-wrapper">CATEGORIES</div>
          </div>
          <div class="KEYBOARD-DRUMS">KEYBOARD<br />DRUMS<br />VIOLIN<br />SINGING</div>
          <div class="rectangle"></div>
          <div class="text-wrapper-2">SELECT</div>
        </div>
      </div>
    </div>
  </body>
</html>

style.css

.box {
  display: flex;
  align-items: flex-start;
  min-width: 430px;
}

.box .iphone-plus {
  position: fixed;
  width: 430px;
  height: 932px;
  z-index: 1;
}

details.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="box"><img class="iphone-plus" src="img/iphone-16-plus-1.svg" /></div>
  </body>
</html>

style.css

.box {
  display: flex;
  align-items: flex-start;
  min-width: 430px;
}

.box .iphone-plus {
  position: fixed;
  width: 430px;
  height: 932px;
  z-index: 1;
}

contact.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-plus">
      <div class="group-wrapper">
        <div class="group">
          <div class="frame">
            <div class="div"></div>
            <div class="text-wrapper">CONTACT US</div>
            <div class="saveetha-gmail-com">
              saveetha@gmail.com<br /><br />ph no:9884572934<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              9264826485
            </div>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>

style.css

.iphone-plus {
background-color: #ffffff;
width: 100%;
min-width: 430px;
min-height: 932px;
display: flex;
}
.iphone-plus group-wrapper {
}
width: 430px;
display: flex;
background-color: #ffffff;
overflow: hidden;
.iphone-plus group {
width: 439px;
display: flex;
}
.iphone-plus.frame {
width: 439px;
height: 932px;
position: relative;
}
.iphone-plus.div {
position: absolute;
top: 0;
left: 0;
width: 430px;
height: 932px;
background-image: url(./img/MUSIC-1.png);
background-size: 100% 100%;
}
iphone-plus.text-wrapper {
position: absolute;
top: 408px;
left: 61px;
font-family: "Inter-BoldItalic", Helvetica;
font-weight: 700;
font-style: italic;
color: #ffffff;
font-size: 48px;
letter-spacing: 0;
line-height: normal;
}
iphone-plus.saveetha-gmail-com {
position: absolute;
top: 758px;
left: 122px;
font-family: "Inter-BoldItalic", Helvetica;
font-weight: 700;
font-style: italic;
color: #ffffff;
font-size: 20px;
letter-spacing: 0;
line-height: normal;
}
```
# OUTPUT:
![alt text](<Screenshot 2025-12-17 161236.png>)
![alt text](<Screenshot 2025-12-18 184204.png>)
![alt text](<Screenshot 2025-12-18 190619.png>)
![alt text](<Screenshot 2025-12-18 191623.png>)
# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
