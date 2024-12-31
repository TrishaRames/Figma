# Ex09 Event Registration Web Application
## Date:20-12-24

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
'''
page 1
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-16-1-1">
<img src="images/node-2.png" class="node-2" alt="whatsapp-image-2024-12-17-at-08-30-19_ccd4d2c0-1" />
<p class="text-3">INDUSTRY 5.0</p>
<p class="text-4">Ready curriculum imparting
21st Century skills</p>
<div class="frame-1-6"></div>
<img src="images/saveetha-college-1-7.png" class="saveetha-college-1-7" alt="saveetha-college-1" />
<p class="text-8">APPLY NOW</p>
</div>

</body>
</html>
/* Add font files for Inria Serif */
@font-face {
  font-family: 'Inria Serif';
  src: url('fonts/inria-serif.woff2') format('woff2'),
       url('fonts/inria-serif.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Inder */
@font-face {
  font-family: 'Inder';
  src: url('fonts/inder.woff2') format('woff2'),
       url('fonts/inder.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-inria-serif: 'Inria Serif', sans-serif;
  --font-family-inder: 'Inder', sans-serif;
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.node-2 {
  position: absolute;
  left: 0px;
  top: -6px;
  width: 388px;
  height: 107px;
  width: 100%;
  height: auto;
}

.text-3 {
  position: absolute;
  left: -36px;
  top: 128px;
  width: 429px;
  height: 65px;
  font-size: 36px;
  font-family: var(--font-family-inria-serif);
  font-weight: normal;
  text-align: center;
  color: rgba(232, 225, 31, 1);
}

.text-4 {
  position: absolute;
  left: -10px;
  top: 150px;
  width: 417px;
  height: 194px;
  font-size: 36px;
  font-family: var(--font-family-inria-serif);
  font-weight: normal;
  text-align: center;
  color: rgba(41, 219, 139, 1);
}

.rectangle-1-5 {
  position: absolute;
  left: 94px;
  top: 696px;
  width: 209px;
  height: 55px;
}

.frame-1-6 {
  position: absolute;
  left: 196px;
  top: 724px;
  width: 78px;
  height: 16px;
}

.saveetha-college-1-7 {
  position: absolute;
  left: 0px;
  top: 344px;
  width: 388px;
  height: 244px;
  width: 100%;
  height: auto;
}

.text-8 {
  position: absolute;
  left: 7px;
  top: 632px;
  width: 381px;
  height: 92px;
  border: 1px solid rgba(255, 255, 255, 1);
  font-size: 36px;
  font-family: var(--font-family-inder);
  font-weight: normal;
  text-align: center;
  color: rgba(255, 255, 255, 1);
}

.iphone-16-1-1 {
  position: absolute;
  left: -197px;
  top: -426px;
  width: 393px;
  height: 852px;
  position: relative;
  width: 100%;
  height: auto;
  background-color: rgba(180, 14, 14, 1);
}
page 2

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-16-2-1">
<p class="text-2">Admissions open 2025</p>
<div class="rectangle-2-3"></div>
<p class="text-4">NAME </p>
<div class="rectangle-3-5"></div>
<p class="text-6">EMAIL ID</p>
<div class="rectangle-4-7"></div>
<p class="text-8">MOBLIE NO</p>
<div class="rectangle-5-9"></div>
<div class="frame-2-10"></div>
<p class="text-11">ANY PASSWORD OF YOUR CHOICE</p>
<div class="rectangle-6-12"></div>
<p class="text-13">STATE</p>
<div class="rectangle-7-14"></div>
<div class="rectangle-8-15"></div>
<p class="text-16">COURSE</p>
<div class="rectangle-9-17"></div>
<p class="text-18">CITY</p>
<p class="text-19">SPECIALIZATION</p>
<div class="rectangle-10-20"></div>
<p class="text-21">CAPCHA</p>
<div class="rectangle-11-22"></div>
<p class="text-23">ENTER AS SHOWN</p>
<div class="rectangle-12-24"></div>
<p class="text-25">APPLY NOW</p>
<img src="images/arrow-1-26.svg" class="arrow-1-26" alt="arrow-1" />
<p class="text-27">Already have an account?Login</p>
<p class="text-28">Resend Verification Email</p>
</div>

</body>
</html>
/* Add font files for Inria Serif */
@font-face {
  font-family: 'Inria Serif';
  src: url('fonts/inria-serif.woff2') format('woff2'),
       url('fonts/inria-serif.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-inria-serif: 'Inria Serif', sans-serif;
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.text-2 {
  position: absolute;
  left: -7.947134494781494px;
  top: 14.904327392578125px;
  width: 397.98321533203125px;
  height: 10.379075050354004px;
  font-size: 36px;
  font-family: var(--font-family-inria-serif);
  font-weight: normal;
  text-align: center;
  color: rgba(255, 255, 255, 1);
}

.rectangle-2-3 {
  position: absolute;
  left: 0px;
  top: 49px;
  width: 390px;
  height: 46px;
  background-color: rgba(217, 217, 217, 1);
}

.text-4 {
  position: absolute;
  left: 18px;
  top: 52px;
  width: 100px;
  height: 43px;
  font-size: 36px;
  font-family: var(--font-family-inria-serif);
  font-weight: normal;
  text-align: center;
  color: rgba(0, 0, 0, 1);
}

.rectangle-3-5 {
  position: absolute;
  left: 0px;
  top: 117px;
  width: 390px;
  height: 52px;
  background-color: rgba(217, 217, 217, 1);
}

.text-6 {
  position: absolute;
  left: 10px;
  top: 122px;
  width: 150px;
  height: 43px;
  font-size: 36px;
  font-family: var(--font-family-inria-serif);
  font-weight: normal;
  text-align: center;
  color: rgba(0, 0, 0, 1);
}

.rectangle-4-7 {
  position: absolute;
  left: 0px;
  top: 206px;
  width: 390px;
  height: 36px;
  background-color: rgba(217, 217, 217, 1);
}

.text-8 {
  position: absolute;
  left: 10px;
  top: 199px;
  width: 186px;
  height: 43px;
  font-size: 36px;
  font-family: var(--font-family-inria-serif);
  font-weight: normal;
  text-align: center;
  color: rgba(0, 0, 0, 1);
}

.rectangle-5-9 {
  position: absolute;
  left: 0px;
  top: 295px;
  width: 390px;
  height: 36px;
  background-color: rgba(217, 217, 217, 1);
}

.frame-2-10 {
  position: absolute;
  left: 139px;
  top: 261px;
  width: 100px;
  height: 100px;
}

.text-11 {
  position: absolute;
  left: 7px;
  top: 299px;
  width: 363px;
  height: 29px;
  font-size: 24px;
  font-family: var(--font-family-inria-serif);
  font-weight: normal;
  text-align: center;
  color: rgba(0, 0, 0, 1);
}

.rectangle-6-12 {
  position: absolute;
  left: 0px;
  top: 382px;
  width: 127px;
  height: 36px;
  background-color: rgba(217, 217, 217, 1);
}

.text-13 {
  position: absolute;
  left: 1px;
  top: 385px;
  width: 67px;
  height: 29px;
  font-size: 24px;
  font-family: var(--font-family-inria-serif);
  font-weight: normal;
  text-align: center;
  color: rgba(0, 0, 0, 1);
}

.rectangle-7-14 {
  position: absolute;
  left: 162px;
  top: 387px;
  width: 228px;
  height: 31px;
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-8-15 {
  position: absolute;
  left: 0px;
  top: 460px;
  width: 139px;
  height: 43px;
  background-color: rgba(217, 217, 217, 1);
}

.text-16 {
  position: absolute;
  left: 6px;
  top: 476px;
  width: 89px;
  height: 29px;
  font-size: 24px;
  font-family: var(--font-family-inria-serif);
  font-weight: normal;
  text-align: center;
  color: rgba(0, 0, 0, 1);
}

.rectangle-9-17 {
  position: absolute;
  left: 195px;
  top: 471px;
  width: 195px;
  height: 32px;
  background-color: rgba(217, 217, 217, 1);
}

.text-18 {
  position: absolute;
  left: 169px;
  top: 385px;
  width: 51px;
  height: 38px;
  font-size: 24px;
  font-family: var(--font-family-inria-serif);
  font-weight: normal;
  text-align: center;
  color: rgba(0, 0, 0, 1);
}

.text-19 {
  position: absolute;
  left: 162px;
  top: 474px;
  width: 247px;
  height: 29px;
  font-size: 24px;
  font-family: var(--font-family-inria-serif);
  font-weight: normal;
  text-align: center;
  color: rgba(0, 0, 0, 1);
}

.rectangle-10-20 {
  position: absolute;
  left: 0px;
  top: 558px;
  width: 127px;
  height: 40px;
  background-color: rgba(217, 217, 217, 1);
}

.text-21 {
  position: absolute;
  left: 19px;
  top: 571px;
  width: 90px;
  height: 29px;
  font-size: 24px;
  font-family: var(--font-family-inria-serif);
  font-weight: normal;
  text-align: center;
  color: rgba(0, 0, 0, 1);
}

.rectangle-11-22 {
  position: absolute;
  left: 150px;
  top: 560px;
  width: 240px;
  height: 38px;
  background-color: rgba(217, 217, 217, 1);
}

.text-23 {
  position: absolute;
  left: 162px;
  top: 562px;
  width: 197px;
  height: 29px;
  font-size: 24px;
  font-family: var(--font-family-inria-serif);
  font-weight: normal;
  text-align: center;
  color: rgba(0, 0, 0, 1);
}

.rectangle-12-24 {
  position: absolute;
  left: 33px;
  top: 650px;
  width: 284px;
  height: 59px;
  background-color: rgba(217, 217, 217, 1);
}

.text-25 {
  position: absolute;
  left: 47px;
  top: 663px;
  width: 259px;
  height: 43px;
  font-size: 36px;
  font-family: var(--font-family-inria-serif);
  font-weight: normal;
  text-align: center;
  color: rgba(0, 0, 0, 1);
}

.arrow-1-26 {
  position: absolute;
  left: 274.9999694824219px;
  top: 690.0000610351562px;
  width: 31.144824981689453px;
  height: 0px;
  border: 2px solid rgba(0, 0, 0, 1);
}

.text-27 {
  position: absolute;
  left: 47px;
  top: 729px;
  width: 286px;
  height: 19px;
  font-size: 16px;
  font-family: var(--font-family-inria-serif);
  font-weight: normal;
  text-align: center;
  color: rgba(255, 255, 255, 1);
}

.text-28 {
  position: absolute;
  left: 68px;
  top: 761px;
  width: 238px;
  height: 19px;
  font-size: 16px;
  font-family: var(--font-family-inria-serif);
  font-weight: normal;
  text-align: center;
  color: rgba(255, 255, 255, 1);
}

.iphone-16-2-1 {
  position: absolute;
  left: 242px;
  top: -426px;
  width: 390px;
  height: 852px;
  position: relative;
  width: 100%;
  height: auto;
  background-color: rgba(28, 104, 115, 1);
}
page 3
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-16-3-1">
<p class="text-2">Thank you</p>
<img src="images/node-3.png" class="node-3" alt="vintage-parchment-texture-0410-5698735-1" />
<p class="text-4">For more information </p>
<p class="text-5">THANK YOU</p>
<p class="text-6">8939902737
044 66726690</p>
<p class="text-7">admission@saveetha.ac.in</p>
</div>

</body>
</html>
:root {
  --font-family-inter: 'Inter', sans-serif;
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.text-2 {
  position: absolute;
  left: 48px;
  top: 305px;
  width: 290px;
  height: 44px;
  font-size: 36px;
  font-family: var(--font-family-inter);
  font-weight: normal;
  text-align: center;
  color: rgba(255, 255, 255, 1);
}

.node-3 {
  position: absolute;
  left: 0px;
  top: 0px;
  width: 393px;
  height: 852px;
  width: 100%;
  height: auto;
}

.text-4 {
  position: absolute;
  left: 0px;
  top: 393px;
  width: 393px;
  height: 44px;
  font-size: 36px;
  font-family: var(--font-family-inter);
  font-weight: normal;
  text-align: center;
  color: rgba(0, 0, 0, 1);
}

.text-5 {
  position: absolute;
  left: 76px;
  top: 253px;
  width: 212px;
  height: 44px;
  font-size: 36px;
  font-family: var(--font-family-inter);
  font-weight: normal;
  text-align: center;
  color: rgba(0, 0, 0, 1);
}

.text-6 {
  position: absolute;
  left: 18px;
  top: 437px;
  width: 375px;
  height: 69px;
  font-size: 32px;
  font-family: var(--font-family-inter);
  font-weight: normal;
  text-align: center;
  color: rgba(0, 0, 0, 1);
}

.text-7 {
  position: absolute;
  left: 18px;
  top: 506px;
  width: 375px;
  height: 90px;
  font-size: 32px;
  font-family: var(--font-family-inter);
  font-weight: normal;
  text-align: center;
  color: rgba(0, 0, 0, 1);
}

.iphone-16-3-1 {
  position: absolute;
  left: 662px;
  top: -426px;
  width: 393px;
  height: 852px;
  position: relative;
  width: 100%;
  height: auto;
  background-color: rgba(200, 65, 70, 1);
}


'''

## OUTPUT:
![alt text](<Screenshot (43).png>)
![alt text](<Screenshot (44).png>)
![alt text](<Screenshot (45).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
