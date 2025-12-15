# Ex04 Places Around Me
## Date: 11/12/2025
## Ref.No:25006077

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
map.html
~~~
<!DOCTYPE html>
<html>
<head>
    <title>My City</title>
</head>
<body>
    <h1 align="center"><font color="red"><b>TIRUVANNAMALAI</b></font></h1>

    <h3 align="center"><font color="blue"><b>K.Sundaresh (25006077)</b></font></h3>

    <img src="map.png" usemap="#MyCity" height="800" width="1550">

    <map name="MyCity">
        <area target="_blank" alt="hometown" title="hometown" href="home.html" coords="1128,637,906,561" shape="rect">
        <area target="_blank" alt="temple" title="temple" href="temple.html" coords="75,685,109" shape="circle">
    </map>
</body>
</html>
~~~
home.html
~~~
<!DOCTYPE html>
<html>
<head>
    <title>HOMETOWN</title>
</head>
<body bgcolor="pink">
    <h1 align="center">
        <font color="red"><b>TIRUVANNAMALAI</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>My Hometown - A Divine Destination</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" size="5">
            Tiruvannamalai is a sacred town in Tamil Nadu, renowned for its spiritual energy and ancient traditions.
            At the heart of the town lies the majestic Arunachaleswarar Temple, dedicated to Lord Shiva, one of the largest temples in India.
            Every full moon, thousands of devotees participate in the *Girivalam*—a sacred 14 km walk around the Arunachala Hill.
            The town is steeped in history, home to mystics like Sri Ramana Maharshi. With its serene landscapes, vibrant festivals, and divine ambiance,
            Tiruvannamalai is not just my hometown—it's a spiritual sanctuary.
        </font>
    </p>
</body>
</html>
~~~
temple.html
~~~
<!DOCTYPE html>
<html>
<head>
    <title>TEMPLE</title>
</head>
<body bgcolor="pink">
    <h1 align="center">
        <font color="red"><b>TIRUVANNAMALAI</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>MURUGAN Temple Devotional Centre</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" size="5">
            The temple's main deity is Lord Murugan, who is worshipped as the god of war and a handsome young man riding a peacock with six faces and twelve arms.
            The idol is made with gold and diamonds. The temple architecture is a fine example of the Dravidian style, with a tall gopuram (gateway tower) at the entrance,
            adorned with intricate carvings. It also has a mandapam (hall) with beautifully carved pillars, which houses the main shrine.
        </font>
    </p>
</body>
</html>
~~~


## OUTPUT

![tvmalai](https://github.com/user-attachments/assets/924919b2-d301-4594-a3e8-5b98a92f0bff)

<img width="1212" height="572" alt="image" src="https://github.com/user-attachments/assets/0160577d-6fdf-42ad-a155-8159c7b32e3b" />

<img width="1210" height="572" alt="image" src="https://github.com/user-attachments/assets/75a67b67-ff21-4ff3-ae56-ed3cec9bbbe6" />













## RESULT
The program for implementing image maps using HTML is executed successfully.
