# Ex09 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```css
FRAME 1:
index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-SE">
      <img class="logo" src="img/logo-1.png" />
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <img class="img" src="img/rectangle-3.svg" />
      <div class="text-wrapper">SPORTS DAY EVENTS</div>
      <div class="text-wrapper-2">LOGIN</div>
      <div class="text-wrapper-3">REGISTER</div>
      <p class="p">DON’T HAVE A ACCOUNT? SIGN UP</p>
    </div>
  </body>
</html>

style.css

.iphone-SE {
  position: relative;
  width: 320px;
  height: 568px;
  overflow: hidden;
  background: linear-gradient(
    0deg,
    rgba(255, 255, 255, 1) 0%,
    rgba(255, 255, 255, 1) 100%
  );
}

.iphone-SE .logo {
  position: absolute;
  top: 0;
  left: 0;
  width: 320px;
  height: 72px;
  aspect-ratio: 4.14;
  object-fit: cover;
}

.iphone-SE .rectangle {
  position: absolute;
  top: 164px;
  left: 66px;
  width: 184px;
  height: 164px;
  background-color: #00000075;
}

.iphone-SE .div {
  position: absolute;
  top: 176px;
  left: 77px;
  width: 162px;
  height: 55px;
  background-color: #d22c2c;
  box-shadow: 0px 4px 4px #00000040, 0px 4px 4px #00000080;
}

.iphone-SE .rectangle-2 {
  position: absolute;
  top: 246px;
  left: 80px;
  width: 162px;
  height: 55px;
  background-color: #d22c2c;
  box-shadow: 0px 4px 4px #00000080;
}

.iphone-SE .img {
  position: absolute;
  top: 215px;
  left: 328px;
  width: 162px;
  height: 55px;
}

.iphone-SE .text-wrapper {
  position: absolute;
  top: 127px;
  left: 35px;
  width: 260px;
  -webkit-text-stroke: 1px #ffffff;
  font-family: "Shrikhand-Regular", Helvetica;
  font-weight: 400;
  color: #0ec6eb;
  font-size: 20px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-SE .text-wrapper-2 {
  position: absolute;
  top: 182px;
  left: 74px;
  width: 157px;
  font-family: "Source Sans 3-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 30px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-SE .text-wrapper-3 {
  position: absolute;
  top: 250px;
  left: 74px;
  width: 157px;
  font-family: "Source Sans 3-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 30px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-SE .p {
  position: absolute;
  top: 310px;
  left: 46px;
  width: 213px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 8px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}
```
```css
FRAME 2:
index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-SE">
      <img class="LOGIN" src="img/LOGIN-1.png" />
      <img class="logo" src="img/logo-2.png" />
      <p class="text-wrapper">LIST OF EVENTS TO PARTICIPATE:</p>
      <div class="div">→ CRICKET</div>
      <div class="text-wrapper-2">→ FOOTBALL</div>
      <div class="text-wrapper-3">→ HOCKEY</div>
      <div class="text-wrapper-4">→ KHO-KHO</div>
      <div class="text-wrapper-5">→ CHESS</div>
      <div class="text-wrapper-6">→ KABADDI</div>
      <div class="text-wrapper-7">→ CARROM</div>
      <div class="text-wrapper-8">→ TENNIS</div>
      <div class="rectangle"></div>
      <div class="text-wrapper-9">NEXT</div>
    </div>
  </body>
</html>

style.css

.iphone-SE {
  overflow: hidden;
  background: linear-gradient(
    0deg,
    rgba(255, 255, 255, 1) 0%,
    rgba(255, 255, 255, 1) 100%
  );
  width: 100%;
  min-width: 320px;
  min-height: 568px;
  position: relative;
}

.iphone-SE .LOGIN {
  position: absolute;
  top: -599px;
  left: -554px;
  width: 1131px;
  height: 1698px;
  aspect-ratio: 0.67;
  object-fit: cover;
}

.iphone-SE .logo {
  position: absolute;
  top: 0;
  left: 0;
  width: 320px;
  height: 78px;
  aspect-ratio: 4.14;
  object-fit: cover;
}

.iphone-SE .text-wrapper {
  position: absolute;
  top: 106px;
  left: 29px;
  font-family: "Lemon-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-SE .div {
  position: absolute;
  top: 151px;
  left: 19px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 21px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-SE .text-wrapper-2 {
  position: absolute;
  top: 187px;
  left: 19px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 21px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-SE .text-wrapper-3 {
  position: absolute;
  top: 223px;
  left: 19px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 21px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-SE .text-wrapper-4 {
  position: absolute;
  top: 259px;
  left: 19px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 21px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-SE .text-wrapper-5 {
  position: absolute;
  top: 295px;
  left: 19px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 21px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-SE .text-wrapper-6 {
  position: absolute;
  top: 151px;
  left: 187px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 21px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-SE .text-wrapper-7 {
  position: absolute;
  top: 187px;
  left: 187px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 21px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-SE .text-wrapper-8 {
  position: absolute;
  top: 223px;
  left: 187px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 21px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-SE .rectangle {
  position: absolute;
  top: 348px;
  left: 104px;
  width: 112px;
  height: 46px;
  background-color: #d22c2c;
  box-shadow: 0px 4px 4px #00000040, 0px 4px 4px #00000080;
}

.iphone-SE .text-wrapper-9 {
  position: absolute;
  top: 351px;
  left: 81px;
  width: 157px;
  font-family: "Source Sans 3-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 30px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}
```
```css
FRAME 3:
index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-SE">
      <img class="LOGIN" src="img/LOGIN-1.png" />
      <img class="img" src="img/LOGIN-2.png" />
      <img class="logo" src="img/logo-2.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">EVENT REGISTRATION FORM:</div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <p class="FULL-NAME"><span class="span">FULL NAME</span> <span class="text-wrapper-2">:</span></p>
      <div class="text-wrapper-3">REG NO:</div>
      <div class="text-wrapper-4">GENDER:</div>
      <div class="text-wrapper-5">EMAIL:</div>
      <div class="text-wrapper-6">PH NO:</div>
      <img class="line" src="img/line-1.svg" />
      <img class="line-2" src="img/line-4.svg" />
      <img class="line-3" src="img/line-5.svg" />
      <img class="line-4" src="img/line-2.svg" />
      <img class="line-5" src="img/line-3.svg" />
      <div class="text-wrapper-7">FILL THE DETAILS*</div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-8">SUBMIT</div>
    </div>
  </body>
</html>

style.css

.iphone-SE {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 320px;
  min-height: 568px;
  position: relative;
}

.iphone-SE .LOGIN {
  top: -599px;
  left: -918px;
  width: 1131px;
  height: 1698px;
  aspect-ratio: 0.67;
  position: absolute;
  object-fit: cover;
}

.iphone-SE .img {
  top: 0;
  left: 0;
  width: 320px;
  height: 568px;
  aspect-ratio: 0.66;
  position: absolute;
  object-fit: cover;
}

.iphone-SE .logo {
  position: absolute;
  top: 0;
  left: 0;
  width: 320px;
  height: 78px;
  aspect-ratio: 4.14;
  object-fit: cover;
}

.iphone-SE .rectangle {
  position: absolute;
  top: 155px;
  left: 26px;
  width: 261px;
  height: 268px;
  background-color: #00000075;
}

.iphone-SE .text-wrapper {
  position: absolute;
  top: 107px;
  left: 53px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-SE .div {
  position: absolute;
  top: 174px;
  left: 40px;
  width: 234px;
  height: 23px;
  background-color: #d9d9d9;
}

.iphone-SE .rectangle-2 {
  position: absolute;
  top: 206px;
  left: 40px;
  width: 168px;
  height: 23px;
  background-color: #d9d9d9;
}

.iphone-SE .rectangle-3 {
  position: absolute;
  top: 238px;
  left: 40px;
  width: 113px;
  height: 23px;
  background-color: #d9d9d9;
}

.iphone-SE .rectangle-4 {
  position: absolute;
  top: 270px;
  left: 40px;
  width: 196px;
  height: 23px;
  background-color: #d9d9d9;
}

.iphone-SE .rectangle-5 {
  position: absolute;
  top: 302px;
  left: 40px;
  width: 196px;
  height: 23px;
  background-color: #d9d9d9;
}

.iphone-SE .FULL-NAME {
  position: absolute;
  top: 178px;
  left: 49px;
  font-family: "Hammersmith One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 12px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-SE .span {
  font-family: "Hammersmith One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 12px;
  letter-spacing: 0;
}

.iphone-SE .text-wrapper-2 {
  font-family: "Irish Grover-Regular", Helvetica;
}

.iphone-SE .text-wrapper-3 {
  position: absolute;
  top: 210px;
  left: 49px;
  font-family: "Hammersmith One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 12px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-SE .text-wrapper-4 {
  position: absolute;
  top: 242px;
  left: 48px;
  font-family: "Hammersmith One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 12px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-SE .text-wrapper-5 {
  position: absolute;
  top: 274px;
  left: 48px;
  font-family: "Hammersmith One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 12px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-SE .text-wrapper-6 {
  position: absolute;
  top: 306px;
  left: 49px;
  font-family: "Hammersmith One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 12px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-SE .line {
  top: 302px;
  left: 94px;
  position: absolute;
  width: 1px;
  height: 23px;
  object-fit: cover;
}

.iphone-SE .line-2 {
  top: 206px;
  left: 102px;
  position: absolute;
  width: 1px;
  height: 23px;
  object-fit: cover;
}

.iphone-SE .line-3 {
  top: 174px;
  left: 116px;
  position: absolute;
  width: 1px;
  height: 23px;
  object-fit: cover;
}

.iphone-SE .line-4 {
  top: 270px;
  left: 94px;
  position: absolute;
  width: 1px;
  height: 23px;
  object-fit: cover;
}

.iphone-SE .line-5 {
  top: 238px;
  left: 97px;
  position: absolute;
  width: 1px;
  height: 23px;
  object-fit: cover;
}

.iphone-SE .text-wrapper-7 {
  position: absolute;
  top: 129px;
  left: 87px;
  font-family: "Content-Regular", Helvetica;
  font-weight: 400;
  color: #de1818;
  font-size: 16px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-SE .rectangle-6 {
  position: absolute;
  top: 345px;
  left: 72px;
  width: 162px;
  height: 55px;
  background-color: #d22c2c;
  box-shadow: 0px 4px 4px #00000040, 0px 4px 4px #00000080;
}

.iphone-SE .text-wrapper-8 {
  position: absolute;
  top: 351px;
  left: 72px;
  width: 157px;
  font-family: "Source Sans 3-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 30px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}
```
## OUTPUT:
<img width="1341" height="763" alt="image" src="https://github.com/user-attachments/assets/aec30678-934c-4ff9-8cb9-c3e00229f965" />


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
