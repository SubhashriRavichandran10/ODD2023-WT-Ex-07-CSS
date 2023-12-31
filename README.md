# Ex-07-CSS
# AIM:
(i) Using CSS media queries, modify the webpage's color scheme with the following requirements:

Default Color Scheme: Background color: Light gray (#f4f4f4) Text color: Dark gray (#333) Link color: Blue (#007bff) Small Screen Adaptation (Max-width: 600px): Change the background color to dark gray (#333)

Change the text color to light gray (#f4f4f4) Change the link color to light green (#28a745) Dark Mode Preference: If the user has set their device to dark mode, override the above styles with the following:

Background color: Black (#000) Text color: White (#fff) Link color: Cyan (#17a2b8) Deliverable: Write the CSS code that implements the above requirements. Your code should include the base styles and the appropriate media queries for small screens and dark mode preference.
# DESIGN STEPS :
# Step 1 :
Create HTML Structure Create the HTML structure for your webpage.

# Step 2 :
Set Default Styles In your CSS file define the default color scheme for the webpage.

#Step 3 :
Implement Small Screen Adaptation Within your CSS file, use a media query to adjust styles for small screens (max-width: 600px).

# Step 4 :
Implement Dark Mode Preference Still in your CSS file, apply another media query to override styles for devices set to dark mode.

# Step 5 :
Add Content In your HTML file, add your webpage content within the 'body' tags.

# Step 6 :
End the code End the html code by closing all the open tages.

# CODE: 7(i)
```
<!Doctype html>
<html>
<head>
<style>
body {
 background-color: #f4f4f4;
 color: #333;
}
a{
color: #007bff;
}
@media screen and (max-width: 600px) 
{
	body{
          background-color: #333;
          color: #f4f4f4;

}
a{
color: #28a745;
}
}
@media(prefers-color-scheme:dark)
{
body
{
background-color: #000;
color: #fff;
}
a
{
color: #17a2b8;
}
}

</style>
</head>
<body>
<h1>webdevelopment tutorial</h1>
<ol>
<li><a href="https://www.w3schools.com/html/">HTML</a></li>
<li><a href="https://www.w3schools.com/js/default.asp">JAVASCRIPT<a/></li>
<li><a href="https://www.w3schools.com/css/default.asp">CSS</a></li>
<li><a href="https://www.w3schools.com/bootstrap/bootstrap_ver.asp">BOOTSRAP</a></li>
</ol>
</body>
</html>
```
# OUTPUT:
![291792174-6aa04563-b317-4969-bc3e-a31bd78ad050](https://github.com/SubhashriRavichandran10/ODD2023-WT-Ex-07-CSS/assets/145743413/c78ef9d6-45d5-4953-8460-1f114ac1bf96)
![291792232-2397d5e4-f903-4d84-9892-09f34c795fc5](https://github.com/SubhashriRavichandran10/ODD2023-WT-Ex-07-CSS/assets/145743413/f0f867e8-3a71-4010-9739-422e90e52b65)

![291792197-1d81c4b9-10cf-465e-bc2d-236aa906efa0](https://github.com/SubhashriRavichandran10/ODD2023-WT-Ex-07-CSS/assets/145743413/234d1949-dc31-4c84-8f02-48be9c3213a1)

# EX-07(ii)-CSS
# AIM:
To use a media query in CSS to apply different styles to a webpage for mobile devices (with widths less than 600px) and desktop devices (with widths greater than or equal to 600px)? Provide an example CSS snippet to demonstrate your answer.

# DESIGN STEPS :EX-7(ii)
# Step 1 :
Create HTML Structure Create the HTML code with root element.

# Step 2 :
Define Default Styles Set the default styles for your webpage that will be applied to all devices.

# Step 3 :
Apply Media Query for Mobile Devices (Max-width: 600px) Use a media query to adjust styles as needed for a mobile-friendly layout.

# Step 4 :
Apply Media Query for Desktop Devices (Min-width: 601px) Use another media query to adjust styles for a larger screen.

# Step 5 :
End the code End the html code by closing all the open tages.

# CODE:7(ii):
```
<!DOCTYPE html>
<html>
<head>
<style type="text/css">
    /* CSS rules for desktop devices */
    body {
        background-color: lightblue;
    }

    /* CSS rules for mobile devices */
    @media only screen and (max-width: 600px) {
        body {
            background-color: lightgreen;
        }
    }
</style>
</head>
<body>
    <div>
       Webdevelopment Tutorial
  </div>
    <ul>
        <li><a href="https://www.saveetha.ac.in/">HTML</a></li>
        <li><a href="http://lms.ai.saveetha.in/my/">JAVASCRIPT</a></li>
        <li><a href="https://www.github.com">CSS</a></li>
        <li><a href="https://www.github.com">BOOTSTRAP</a></li>
  </body>
  </html>
  ```
# OUTPUT:
![291792272-f67a07a6-6814-47b7-9988-80bc4595a8be](https://github.com/SubhashriRavichandran10/ODD2023-WT-Ex-07-CSS/assets/145743413/efc8ece0-f879-49be-b5d3-a68b8ec30abd)
![291792294-59730efb-b456-48f5-a848-89214d06adca](https://github.com/SubhashriRavichandran10/ODD2023-WT-Ex-07-CSS/assets/145743413/d6654153-bd32-4cc9-a22e-3eb88a1f8aa4)


# EX-07(iii)-CSS
# AIM:
To know you can use CSS media queries to apply different styles based on the orientation (landscape or portrait) of the device. Provide a CSS example where you change the background color of the body based on the orientation.

# STEP1:
create a html code by entering basic root tags

# STEP2:
use media queries and add the needed orientation there

# STEP3:
After selecting the screen method then type and then (orientation: your required orientation) if you want portrait you can add there

# STEP4:
Type portrait and landscape there

# STEP5:
Enter the required style for it

# STEP6:
Run the html code in both landscape and portrait mode

# CODE:7(iii)
```
<!Doctype html>
<html>
<head>
<style>
@media only screen and (orientation: portrait) {
	body{
          background-color: #F86ED9;
          color: black;
	 

 }
}
@media only screen and (orientation: landscape) {
  body {
background-color: #6B7576;
color: #4D1B1B;

  }
}

</style>
</head>
<body>
<h1>webdevelopment tutorial</h1>
<ol>
<li><a href="https://www.w3schools.com/html/">HTML</a></li>
<li><a href="https://www.w3schools.com/js/default.asp">JAVASCRIPT</a></li>
<li><a href="https://www.w3schools.com/css/default.asp">CSS</a></li>
<li><a href="https://www.w3schools.com/bootstrap/bootstrap_ver.asp">BOOTSRAP</a></li>
</ol>
</body>
</html>
```
# OUTPUT:
![291792338-5d22a2be-0a1d-4316-9e10-2bfc69ed5c3e](https://github.com/SubhashriRavichandran10/ODD2023-WT-Ex-07-CSS/assets/145743413/87155a1b-7b15-4c1a-8d0f-47de7b71f098)


# EX-07-CSS:7(iv)
# AIM:
TO Describe how you would use media queries to adjust typography (like font size and line spacing) on a website to improve readability across different device sizes, from mobile phones to large desktop monitors. Include a CSS code snippet in your explanation.

# DESIGN STEPS:
# STEP1:
Include media queries

# STEP2:
Enter the required widtth based on your required devices

# STEP3:
Type media queries separately for the devices you are looking for,i gave the code for 3 devices.

# STEP4:
Then enter the font size and line height as your wish ,in benefit of the user.

# STEP5:
Run this html code in browser and observe the changes when you change the size of your desktop

# STEP6:
Take screenshots of the outputs and upload it

# CODE:7(iv)
```
<!Doctype html>
<html>
<head>
<style>
@media screen and (max-width: 499px) 
{
	body{
	  font-size: 23px;
	  line-height:1;

}
}
@media screen and (min-width: 639px)
{
body
{
font-size=20px;
line-height=1;
}
}
@media screen and (min-width: 900)
{
body
{
font-size:15px;
line-height=1;
}
}
</style>
</head>
<body>
<h1>webdevelopment tutorial</h1>
<ol>
<li><a href="https://www.w3schools.com/html/">HTML</a></li>
<li><a href="https://www.w3schools.com/js/default.asp">JAVASCRIPT</a></li>
<li><a href="https://www.w3schools.com/css/default.asp">CSS</a></li>
<li><a href="https://www.w3schools.com/bootstrap/bootstrap_ver.asp">BOOTSRAP</a></li>
</ol>
</body>
</html>
```
# OUTPUT:
![291792408-022141ba-6be3-4fb1-91e1-52789e87d7b1](https://github.com/SubhashriRavichandran10/ODD2023-WT-Ex-07-CSS/assets/145743413/db5baccf-cffe-4327-a7e1-34f6ed07df8f)



# EX-07(V)-CSS:
# AIM:
Media queries can be used to provide print-friendly styles for web pages. How would you use a media query to change the styling of a webpage when it is printed, such as changing the background to white and hiding non-essential elements? Provide a CSS example.

# DESIGN STEPS:
# Step 1 :
Create HTML Structure Create the HTML code with root element.

# Step 2 :
Set Default Styles Define the default styles for your webpage.

# Step 3 :
Apply Media Query for Print Styles Use a media query (@media print) to modify the appearance of the page when it's printed.

# Step 4 :
End the code End the html code by closing all the open tages.

# CODE:7(V)
```
<html>
<head>
<title>Question 05</title>
<style>
    div, li {
        font-size: 14px;
        line-height: 1;
    }

    @media print {
        body {
            background-color: white;
        }

        div, li {
            font-size: 12px;
            line-height: 1.4;
        }

        
        .non-essential {
            display: none;
        }
    }
</style>
</head>
<body>
    <div>
    webdevelopment
  </div>
    <ol>
<li><a href="https://www.w3schools.com/html/">HTML</a></li>
<li><a href="https://www.w3schools.com/js/default.asp">JAVASCRIPT</a></li>
<li><a href="https://www.w3schools.com/css/default.asp">CSS</a></li>
<li><a href="https://www.w3schools.com/bootstrap/bootstrap_ver.asp">BOOTSRAP</a></li>
</ol>
  </body>
  </html>
  ```
# OUTPUT:
![291792479-bb1b5cba-7b07-4750-a250-4c6a240cd6a4](https://github.com/SubhashriRavichandran10/ODD2023-WT-Ex-07-CSS/assets/145743413/d317c546-81e5-4ad2-85f8-0168e91ce804)
![291792501-865d65ba-3441-4773-b70c-e7a92dab6e5f](https://github.com/SubhashriRavichandran10/ODD2023-WT-Ex-07-CSS/assets/145743413/d5e31f52-ee23-45a1-b096-8f2d902d63c4)



# EX-07(vi)-CSS:
# AIM:
With the increasing popularity of dark mode in user interfaces, explain how you would use a media query to detect if the user has set their system to prefer a dark color scheme. Provide an example of how you would change the background and text colors of a website based on this preference.

# DESIGN STEPS:
# STEP1:
Use the prefers-color-scheme media feature, which is used to detect if the user has requested the system use a light or dark color theme.

# STEP2:
The prefers-color-scheme media feature can have the values light, dark, or no-preference.

# STEP3:
use media queries and apply variety of styles that the user prefers

# step4:
set a colour for dark theme

# STEP5:
set a colour for light theme

# STEP6:
enter the required details and links in between the body tag

# step7:
run this code in both light and dark theme

# CODE:7(Vi)
```
<!Doctype html>
<html>
<head>
<style>
@media screen and (prefers-color-scheme:dark) 
{
	body{
          background-color: #FFC203;
          color: red;
	  font-size: 14px;

}
}
@media screen and (prefers-color-scheme:light)
{
body
{
background-color: #03FF5B;
color: #DF5755;
font-size=16px;
}
}

</style>
</head>
<body>
<h1>webdevelopment tutorial</h1>
<ol>
<li><a href="https://www.w3schools.com/html/">HTML</a></li>
<li><a href="https://www.w3schools.com/js/default.asp">JAVASCRIPT<a/></li>
<li><a href="https://www.w3schools.com/css/default.asp">CSS</a></li>
<li><a href="https://www.w3schools.com/bootstrap/bootstrap_ver.asp">BOOTSRAP</a></li>
</ol>
</body>
</html>
```
# OUTPUT:
![291792598-6327029d-11cd-4297-a040-71717b471eb3](https://github.com/SubhashriRavichandran10/ODD2023-WT-Ex-07-CSS/assets/145743413/059030a0-fcac-4dc1-a703-3d0ccbd9123c)
![291792911-da3e0ba5-9a54-4c96-88d9-9a07b156bd4c](https://github.com/SubhashriRavichandran10/ODD2023-WT-Ex-07-CSS/assets/145743413/c95e5606-298f-4e86-9071-baae94bf270e)
