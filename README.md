# Ex04 Places Around Me
## Date: 

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
# map.html
<!DOCTYPE html>
<html>
<head>
    <title>Andhra pradesh</title>
</head>
<body>
    <h1 align="center">
    <font color="black"><b>Hanshika Varthini (212223240046)</b></font>
    </h1>
    <img src="c:\Users\admin\Pictures\Screenshots\map1.png" alt="Workplace" usemap="#workmap" height="650" width="1465">
    <map name="workmap">
        <area shape="circle" coords="700,250,30" alt="Amaravati" href="amaravati.html">
        <area shape="circle" coords="1050,150,30" alt="Visakhapatnam" href="visakhapatnam.html">
        <area shape="circle" coords="350,350,30" alt="kurnool" href="kurnool.html">
        <area shape="circle" coords="270,450,30" alt="tirupati" href="tirupati.html">
        <area shape="circle" coords="625,480,30" alt="nellore" href="nellore.html">
    </map>
</body>
</html>
```
# amaravathi.html
```
<html>
    <head>
        <title>Amaravati</title>
    </head>
    <body style="background-color: deepskyblue;">
        <center>
            <h1 style="color: red;letter-spacing: 2px;">Andhra pradesh</h1>
            <h3 style="color: white; letter-spacing: 2px;">Amaravati</h3>
            <hr>
            <p style="font-size: 20px;">Amaravati is the greenfield capital of the Indian state of Andhra Pradesh. It is situated at the heart of the state, on the right bank of the river Krishna in Guntur district. The name “Amaravati” translates to ‘the place for immortals’ and has historical, spiritual, and mythological significance. The region near Guntur and Vijayawada was identified as the capital, supported by both the government and opposition parties.</p>
        </center>
    </body>
</html>
```
# visakhapatnam.html
```
<html>
    <head>
        <title>Visakhapatnam</title>
    </head>
    <body style="background-color: pink;">
        <center>
            <h1 style="color: rgb(255, 0, 128);letter-spacing: 2px;">Andhra pradesh </h1>
            <h3 style="color: white; letter-spacing: 2px;">Visakhapatnam</h3>
            <hr>
            <p style="font-size: 20px;">Visakhapatnam, also known as Vizag, is the largest and most populous metropolitan city in the Indian state of Andhra Pradesh. Situated between the Eastern Ghats and the Bay of Bengal, Visakhapatnam is a significant city on the east coast of India. It is renowned for its historical significance dating back to the 6th century BCE, when it was ruled by various dynasties like the Andhra Satavahanas, Vengi, Pallava, and Eastern Ganga.</p>
        </center>
    </body>
</html>
```
# kurnool.html
```
<html>
    <head>
        <title>Kurnool</title>
    </head>
    <body style="background-color:yellow">
        <center>
            <h1 style="color: rgb(255, 0, 128);letter-spacing: 2px;">Andhra pradesh</h1>
            <h3 style="color: white; letter-spacing: 2px;">Kurnool</h3>
            <hr>
            <p style="font-size: 20px;">Kurnool district is one of the eight districts in the Rayalaseema region of the Indian state of Andhra Pradesh after the districts are reorganised in April 2022.[1] It is located in the north western part of the state and is bounded by Nandyal district in the east, Anantapur district in the south, Raichur district of Karnataka in the northwest, Bellary district of Karnataka in the west, and Jogulamba Gadwal district of Telangana in the north. It has a population of 2,271,686 based on the 2011 census. The city of Kurnool is the headquarters of the district.Konda Reddy Fort, Mantralayam and Orvakal Rock Garden, Kurnool are tourist places of interest in the district.</p>
        </center>
    </body>
</html>
```
# tirupati.html
```
<html>
    <head>
        <title>Tirupati</title>
    </head>
    <body style="background-color: rgb(0, 255, 179);">
        <center>
            <h1 style="color: rgb(255, 0, 128);letter-spacing: 2px;">Andhra pradesh</h1>
            <h3 style="color: white; letter-spacing: 2px;">Tirupati</h3>
            <hr>
            <p style="font-size: 20px;">Tirupati is a city in the Indian state of Andhra Pradesh known for its historical temples, most notably the Tirumala Venkateshwara Temple. It is one of the eight Svayam vyakta kshetras dedicated to Vishnu and has a rich cultural and religious significance. The city has a population of around 459,985 as of 2011 and is recognized for its heritage and religious importance.The Tirumala Venkateswara Temple in Tirupati is a significant Hindu temple dedicated to Venkateswara, a form of Vishnu believed to have come to earth to alleviate the troubles of Kali Yuga. The temple, managed by Tirumala Tirupati Devasthanams (TTD), is one of the Pancha Kshethram where Maha Lakshmi was born. It is situated on the hills of Tirumala and is considered one of the most important pilgrimage centers in India.</p>
        </center>
    </body>
</html>
```
# Nellore.html
```
<html>
    <head>
        <title>Nellore</title>
    </head>
    <body style="background-color: rgb(255, 157, 0);">
        <center>
            <h1 style="color: rgb(255, 0, 128);letter-spacing: 2px;">Andhra Pradesh/h1>
            <h3 style="color: white; letter-spacing: 2px;">Nellore</h3>
            <hr>
            <p style="font-size: 20px;">Nellore is one of the most important cities and municipal corporations in the state of Andhra Pradesh situated on the banks of the Penneru River. It is also the sixth most populous city in this state. Nellore city is the administrative headquarters of Sri Potti Sri Ramulu Nellore district. Hyderabad, the state capital of Andhra Pradesh, is around 450 kilometer away from Nellore.  Nellore is situated on the Chennai-Kolkata Highway, or NH 5, which is an integral part of the Golden Quadrilateral Expressway Project undertaken by the Indian Government. Nellore is known for the production of mica and gold jewellery. Apart from these two, aquaculture and cultivation of paddy are two very important engagements of the people of Nellore.</p>
        </center>
    </body>
</html>
```
## OUTPUT
![Screenshot 2024-05-07 114740](https://github.com/hanshika-773/NearMe/assets/153576501/34ec9a40-2b61-41c8-8cba-72c475630768) 
![Screenshot 2024-05-07 113624](https://github.com/hanshika-773/NearMe/assets/153576501/499b493d-47db-41fd-ad45-3082c62cb06b)
![Screenshot 2024-05-07 113956](https://github.com/hanshika-773/NearMe/assets/153576501/7044eecd-de5c-4bb4-8798-fb7c21772868)
![Screenshot 2024-05-07 114036](https://github.com/hanshika-773/NearMe/assets/153576501/79ec12d0-bb0e-4c50-ac21-250bbd4107fe)
![Screenshot 2024-05-07 114051](https://github.com/hanshika-773/NearMe/assets/153576501/258cca87-8d8a-443e-bccd-20782ddd716c)
![Screenshot 2024-05-07 114104](https://github.com/hanshika-773/NearMe/assets/153576501/066919f1-2d29-4877-a59b-b94be3f2e522)



## RESULT
The program for implementing image maps using HTML is executed successfully.
