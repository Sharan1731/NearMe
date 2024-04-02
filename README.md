# Ex04 Places Around Me
## Date: 1.04.2024

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
<html>
    <head>
        <title>Chennai</title>
    </head>
    <body bgcolor="cyan">
        <h1> CHENNAI CITY</h1>
        <h3>Name:SHARAN.G</h3>
        <h3>Reg no:212223230203</h3>
<img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Anna Nagar" title="Anna nagar colony" href="1.html" coords="1557,586,1342,535" shape="rect">
    <area target="" alt="Koyambedu" title="Komyambedu" href="2.html" coords="640,228,852,228,642,275,867,275,847,231,779,245,623,279" shape="poly">
    <area target="" alt="Perambur" title="Perambur" href="3.html" coords="734,570,891,604" shape="rect">
    <area target="" alt="Avadi" title="Avadi" href="4.html" coords="1337,310,1107,257" shape="rect">
    <area target="" alt="Royaburam" title="Royaburam" href="5.html" coords="1140,768,1308,809" shape="rect">
</map>
    </body>
</html>


1.html
<html>
<head>
    <title>Anna Nagar</title>
</head>
<body bgcolor="blue">
    <h1>Chennai</h1>
    <h2>Anna Nagar colony</h2>
    <hr>
    <p>Anna Nagar (formerly known as Naduvakkarai),[1] is a neighbourhood in the metropolitan city of Chennai, India. Named after former chief minister of Tamil Nadu C. N. Annadurai, it is located in the north-western part of Chennai and forms a part of the Aminjikarai taluk and the Anna Nagar Zone. It is one of the prime residential areas in Chennai and is home to several prominent doctors, lawyers and politicians. Real estate prices are among the highest in the city.[2] A recent addition to the area is VR Chennai Mall, located near Shanthi Colony and Thirumangalam junction.</p>
</body>
</html>

2.html
<html>
<head>
    <title>koyambedu</title>
</head>
<body bgcolor="#43d4e6">
    <h1>Chennai</h1>
    <h2>Koyambedu</h2>
    <hr>
    <p>Koyambedu is a neighbourhood in Chennai, India. Situated in the western part of Chennai city, the Koyambedu area has become a major hub of activity in Chennai City after the inauguration of the Koyambedu market in 1996 and the Chennai Mofussil Bus Terminus (CMBT) in 2002. The area is active round the clock owing to the movement of people and goods through the day, with uninterrupted transport facilities such as long-route buses, autos, share autos, vegetable goods carriers and so forth.
    </p>
</body>
</html>

3.html
<html>
<head>
    <title>Perabur</title>
</head>
<body bgcolor="#e5f240">
    <h1>Chennai CITY</h1>
    <h2>Perabur</h2>
    <hr>
    <p> Perambur has a notable railway town in the Indian Railways landscape as it is home to the Vande Bharat Express, produced at the Integral Coach Factory located here and also the presence of Chennai Rail Museum, in addition to the railway station serving to decongest the Chennai Central station by serving as a major alighting point for long distance trains passing through or terminating in the city from the North-Western end. The Perambur railway station is considered as the oldest railway station in the city after Royapuram   </p>
</body>
</html>

4.html
<html>
<head>
    <title>Avadi</title>
</head>
<body bgcolor="#46ed9b">
    <h1>Chennai CITY</h1>
    <h2>Avadi</h2>
    <hr>
    <p>
Avadi (Tamil: [aːʋaɖi]) is a western suburb of Chennai, and the headquarters of Avadi taluk located within the Thiruvallur district of Tamil Nadu, India. Situated at about 22 kilometres (14 mi) from Chennai Central Railway Station, it is one of the four municipal corporations in the Chennai Metropolitan Area and is governed by the Avadi Municipal Corporation. It is surrounded by major defence establishments and is home to various universities and engineering colleges. The neighborhood is served by Avadi Railway Station of the Chennai Suburban Railway. 
    </p>
</body>
</html>

5.html
<html>
<head>
    <title>Royaburam</title>
</head>
<body bgcolor="#f048a7">
    <h1>Chennai CITY</h1>
    <h2>Royaburam</h2>
    <hr>
    <p>
The region existed as a well known settlement during the Chola times, but the name Royapuram is derived from a Tamil appellation for St. Peter, Royappa, in connection with St. Peter's Church in the area.[2] The region was originally called Rayarapuram named after the Rayar Kings who rules down South. It is also believed that the British / Anglo Indians settled in this locality were called Rayars, which lent the name Rayarpuram.[3]
    </p>
</body>
</html>
```
## OUTPUT
![alt text](<Screenshot 2024-04-01 153144-1.png>)
![alt text](<Screenshot 2024-04-02 105251.png>)
![alt text](<Screenshot 2024-04-02 111346.png>)
![alt text](<Screenshot 2024-04-02 105355.png>)
![alt text](<Screenshot 2024-04-02 105447.png>)
![alt text](<Screenshot 2024-04-02 105429-1.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
