# Ex08 Event Registration Web Application
## Date:19/12/2025

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
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
    <div class="box"><div class="rectangle"></div></div>
  </body>
</html>

globals.css
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css
.box {
  width: 540px;
  height: 874px;
}

.box .rectangle {
  position: fixed;
  top: 0;
  left: 0;
  width: 540px;
  height: 874px;
}

```
```
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
    <div class="android-medium">
      <img class="union" src="img/union.svg" />
      <img class="star" src="img/star-1.svg" />
      <img class="img" src="img/star-2.svg" />
      <div class="text-wrapper">Events:</div>
      <div class="div">Treasure hunt</div>
      <img class="star-2" src="img/star-3.svg" />
      <div class="text-wrapper-2">Bug bounty</div>
      <img class="star-3" src="img/star-4.svg" />
      <div class="text-wrapper-3">Logo design</div>
      <img class="star-4" src="img/star-5.svg" />
      <div class="text-wrapper-4">Dance</div>
      <img class="star-5" src="img/star-6.svg" />
      <div class="sing">Sing</div>
      <img class="star-6" src="img/star-7.svg" />
      <img class="star-7" src="img/star-8.svg" />
      <div class="text-wrapper-5">whats the word?</div>
      <img class="vector" src="img/vector-3.svg" />
      <img class="vector-2" src="img/vector-4.svg" />
    </div>
  </body>
</html>

globals.css
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css
.android-medium {
  border: 25px solid;
  border-color: transparent;
  border-image: conic-gradient(
      from 360deg at 50% 50%,
      rgba(235, 120, 120, 0.9) 9%,
      rgba(94, 94, 94, 0.9) 41%,
      rgba(94, 94, 94, 0.9) 62%,
      rgba(102, 102, 102, 0.9) 79%
    )
    1;
  background: linear-gradient(
    0deg,
    rgba(255, 255, 255, 1) 0%,
    rgba(255, 255, 255, 1) 100%
  );
  width: 100%;
  min-width: 547px;
  min-height: 917px;
  position: relative;
}

.android-medium .union {
  position: absolute;
  top: 55px;
  left: 78px;
  width: 449px;
  height: 57px;
}

.android-medium .star {
  position: absolute;
  top: 20px;
  left: 36px;
  width: 119px;
  height: 127px;
}

.android-medium .img {
  position: absolute;
  top: 201px;
  left: 84px;
  width: 39px;
  height: 38px;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 55px;
  left: 231px;
  font-family: "Denk One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 40px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  position: absolute;
  top: 193px;
  left: 132px;
  font-family: "Denk One-Regular", Helvetica;
  font-weight: 400;
  color: #2b043a;
  font-size: 40px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .star-2 {
  position: absolute;
  top: 290px;
  left: 84px;
  width: 39px;
  height: 38px;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 286px;
  left: calc(50.00% - 142px);
  font-family: "Denk One-Regular", Helvetica;
  font-weight: 400;
  color: #2b043a;
  font-size: 40px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .star-3 {
  position: absolute;
  top: 379px;
  left: 84px;
  width: 39px;
  height: 38px;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 375px;
  left: 132px;
  font-family: "Denk One-Regular", Helvetica;
  font-weight: 400;
  color: #2b0339;
  font-size: 40px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .star-4 {
  position: absolute;
  top: 468px;
  left: 84px;
  width: 39px;
  height: 38px;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 460px;
  left: 132px;
  font-family: "Denk One-Regular", Helvetica;
  font-weight: 400;
  color: #2b0339;
  font-size: 40px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .star-5 {
  position: absolute;
  top: 552px;
  left: 84px;
  width: 39px;
  height: 38px;
}

.android-medium .sing {
  position: absolute;
  top: 544px;
  left: 132px;
  font-family: "Denk One-Regular", Helvetica;
  font-weight: 400;
  color: #2b043a;
  font-size: 40px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .star-6 {
  position: absolute;
  top: 639px;
  left: 84px;
  width: 39px;
  height: 38px;
}

.android-medium .star-7 {
  position: absolute;
  top: 703px;
  left: 490px;
  width: 54px;
  height: 51px;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 631px;
  left: 132px;
  font-family: "Denk One-Regular", Helvetica;
  font-weight: 400;
  color: #2b0339;
  font-size: 40px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .vector {
  position: absolute;
  top: 668px;
  left: 193px;
  width: 327px;
  height: 249px;
}

.android-medium .vector-2 {
  position: absolute;
  top: 671px;
  left: 195px;
  width: 328px;
  height: 246px;
}
```
```
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
    <div class="android-medium">
      <img class="union" src="img/union.svg" />
      <img class="star" src="img/star-1.svg" />
      <div class="text-wrapper">Event registration form</div>
      <img class="img" src="img/star-8.svg" />
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="text-wrapper-2">Full name</div>
      <div class="text-wrapper-3">Gender</div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-4">Age</div>
      <div class="text-wrapper-5">Register No.</div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper-6">Department</div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-7">Mobile No.</div>
      <div class="text-wrapper-8">Email ID</div>
      <img class="rectangle-7" src="img/rectangle-15.svg" />
      <div class="rectangle-8"></div>
      <div class="events-registered">Events <br />registered</div>
      <div class="text-wrapper-9">Submit</div>
      <img class="line-stroke" src="img/line-2-stroke.svg" />
    </div>
  </body>
</html>

globals.css
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css
.android-medium {
  border: 25px solid;
  border-color: transparent;
  border-image: conic-gradient(
      from 360deg at 50% 50%,
      rgba(235, 120, 120, 0.9) 9%,
      rgba(94, 94, 94, 0.9) 41%,
      rgba(94, 94, 94, 0.9) 62%,
      rgba(102, 102, 102, 0.9) 79%
    )
    1;
  background: linear-gradient(
    0deg,
    rgba(255, 255, 255, 1) 0%,
    rgba(255, 255, 255, 1) 100%
  );
  width: 100%;
  min-width: 547px;
  min-height: 917px;
  position: relative;
}

.android-medium .union {
  position: absolute;
  top: 55px;
  left: 108px;
  width: 419px;
  height: 100px;
}

.android-medium .star {
  position: absolute;
  top: 24px;
  left: 23px;
  width: 121px;
  height: 129px;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 55px;
  left: 131px;
  width: 351px;
  font-family: "Denk One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 40px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .img {
  position: absolute;
  top: 756px;
  left: 390px;
  width: 135px;
  height: 132px;
}

.android-medium .rectangle {
  position: absolute;
  top: 174px;
  left: 45px;
  width: 321px;
  height: 46px;
  background-color: #dec1ea;
  border-radius: 10px;
}

.android-medium .div {
  position: absolute;
  top: 230px;
  left: 45px;
  width: 321px;
  height: 46px;
  background-color: #dec1ea;
  border-radius: 10px;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 174px;
  left: 62px;
  font-family: "Do Hyeon-Regular", Helvetica;
  font-weight: 400;
  color: #6e6969;
  font-size: 40px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 230px;
  left: 62px;
  font-family: "Do Hyeon-Regular", Helvetica;
  font-weight: 400;
  color: #6e6969;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 286px;
  left: 45px;
  width: 321px;
  height: 46px;
  background-color: #dec1ea;
  border-radius: 10px;
}

.android-medium .rectangle-3 {
  position: absolute;
  top: 342px;
  left: 45px;
  width: 321px;
  height: 46px;
  background-color: #dec1ea;
  border-radius: 10px;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 286px;
  left: 62px;
  font-family: "Do Hyeon-Regular", Helvetica;
  font-weight: 400;
  color: #6e6969;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 342px;
  left: 62px;
  font-family: "Do Hyeon-Regular", Helvetica;
  font-weight: 400;
  color: #6e6969;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-4 {
  position: absolute;
  top: 398px;
  left: 45px;
  width: 321px;
  height: 46px;
  background-color: #dec1ea;
  border-radius: 10px;
}

.android-medium .text-wrapper-6 {
  position: absolute;
  top: 398px;
  left: 62px;
  font-family: "Do Hyeon-Regular", Helvetica;
  font-weight: 400;
  color: #6e6969;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-5 {
  position: absolute;
  top: 454px;
  left: 45px;
  width: 321px;
  height: 46px;
  background-color: #dec1ea;
  border-radius: 10px;
}

.android-medium .rectangle-6 {
  position: absolute;
  top: 510px;
  left: 45px;
  width: 321px;
  height: 46px;
  background-color: #dec1ea;
  border-radius: 10px;
}

.android-medium .text-wrapper-7 {
  position: absolute;
  top: 454px;
  left: 62px;
  font-family: "Do Hyeon-Regular", Helvetica;
  font-weight: 400;
  color: #6e6969;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-8 {
  position: absolute;
  top: 510px;
  left: 62px;
  font-family: "Do Hyeon-Regular", Helvetica;
  font-weight: 400;
  color: #6e6969;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-7 {
  position: absolute;
  top: 742px;
  left: 129px;
  width: 153px;
  height: 46px;
}

.android-medium .rectangle-8 {
  position: absolute;
  top: 566px;
  left: 45px;
  width: 321px;
  height: 136px;
  background-color: #dec1ea;
  border-radius: 10px;
}

.android-medium .events-registered {
  position: absolute;
  top: 566px;
  left: 62px;
  font-family: "Do Hyeon-Regular", Helvetica;
  font-weight: 400;
  color: #6e6969;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-9 {
  position: absolute;
  top: 742px;
  left: 147px;
  font-family: "Do Hyeon-Regular", Helvetica;
  font-weight: 400;
  color: #f99f29;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .line-stroke {
  position: absolute;
  top: 173px;
  left: 452px;
  width: 7px;
  height: 566px;
}
```

## OUTPUT:
![alt text](<Screenshot (164).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
