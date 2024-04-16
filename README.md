# Ex04 Places Around Me
## Date: 16-04-2024

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```

Developed by :HARIPRASHAAD RA
Register Number :212223040060
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            background-color: aqua;
        }
        
    </style>
</head>
<body>
    <img src="d2.png" alt="" height = "530" usemap = "#MapNew" onmousemove = "coordinate(event)">
    <map name="MapNew">
        <area shape="RECT" coords="234,189,267,244" href="https://www.careerindia.com/colleges/c-t-m-college-of-arts-and-science-chennai-tamil-nadu-cp2816/" alt="ctm college">
        <area shape="RECT" coords="366,311,389,280" href="https://www.sreesasthaarts.in/" alt="sree sasthaa">
        <area shape="rect" coords="223,231,267,340" href="https://dmice.ac.in/" alt="dmice">
        <area shape="rect" coords="50,240,76,250" href="https://www.apolloartsandsciencecollegechennai.ac.in/about.aspx" alt="apollo arts and science">
        <area shape="rect" coords="197,468,220,498" href="https://lakeviewlifecentre.org/" alt="lakeview">
    </map><br>
    
    
   
</body>
</html>
```

## OUTPUT







## RESULT
The program for implementing image maps using HTML is executed successfully.
