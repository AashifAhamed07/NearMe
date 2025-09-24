# Ex04 Places Around Me
## Date:24.09.2025 

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
map.html
<html>
    <head>
        <title>Web ex-4</title>
    </head>
    <body>
        <h1 align="center">VILLUPURAM CITY</h1>
        <h2 align="center">Aashif Ahamed S-(25013503)</h2>
<img src="Map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Kannika Parameshwari Textile Store" title="Kannika Parameshwari Textile Store" href="textile.html" coords="1084,102,1343,20" shape="rect">
    <area target="" alt="Kalyan Cinemas" title="Kalyan Cinemas" href="cinema.html" coords="672,740,857,671" shape="rect">
    <area target="" alt="Thangamayil Jewellery" title="Thangamayil Jewellery" href="jewellery.html" coords="1169,443,1361,348" shape="rect">
    <area target="" alt="Ragavendra Temple" title="Ragavendra Temple" href="temple.html" coords="49,128,304,132,160,202" shape="poly">
    <area target="" alt="E.S Hospital" title="E.S Hospital" href="hospital.html" coords="420,820,84" shape="circle">
</map>
    </body>
</html>
cinema.html
<html>
    <head>
        <title>Kalyan</title>
    </head>
    <body bgcolor="black" text="white">
        <h2 align="center">Kalyan Cinemas</h2>
        <pre align="center">
        It is the theatre which people come and watch
        latest movies since 1990 and Now this is a
        comfortable spot for watching movies
        </pre>
    </body>
</html>
hospital.html
<html>
    <head>
        <title>E.S</title>
    </head>
    <body bgcolor="green" text="white">
        <h2 align="center">E.S Hospital</h2>
        <pre align="center">
        It is a hospital in which people came for treatment
        it is a good and hygienic hospital but bills 
        are at high cost
        </pre>
    </body>
</html>
jewellery.html
<html>
    <head>
        <title>Thangamayil</title>
    </head>
    <body bgcolor="yellow">
        <h2 align="center">Thangamayil Jewellery</h2>
        <pre align="center">
    It is a jewellery shop in which golds,diamonds
    are available in affordable price which people
    come and buy jewels for special function 
        </pre>
    </body>
</html>
temple.html
<html>
    <head>
        <title>temple</title>
    </head>
    <body bgcolor="sky blue" text="gold">
        <h2 align="center">Sri Ragavendra Temple</h2>
        <pre align="center">
        It is a traditonal temple in which people come and
        pray god it will give a positive feel when enter this 
        temple and left the temple with half-minded
        </pre>
    </body>
</html>
textile.html
<html>
    <head>
        <title>Textile</title>
    </head>
    <body bgcolor="purple" text="white">
        <h2 align="center">Kannika Parameshwari</h2>
        <pre align="center">
        It is a textile shop which provides more offers and clothes are available 
        in affordable price and also the clothes are good quality and give extra
        offers if you buy clothes more than 10k
        </pre>
    </body>
</html>
```
## OUTPUT
![alt text](<Screenshot (11)-1.png>)
![alt text](<Screenshot (12)-2.png>)
![alt text](<Screenshot (13).png>)
![alt text](<Screenshot (14).png>)
![alt text](<Screenshot (15).png>)
![alt text](<Screenshot (16).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
