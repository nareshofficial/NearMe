# Ex04 Places Around Me
## Date: 13-10-2024

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
```
<html>
    <head>
        <title>
            My City
        </title>
    </head>
    <body>
        <h1 align="center">
            <font color="magenda"><b>KADAPA</b></font>
        </h1>
        <h3 align="center">
            <font color="black"><b>Atluru Sai Vardhan Reddy (212221040022)</b></font>
        </h3>
        <center>
            
<map name="MyCity">
    <area shape="rect" coords="100,100,900,900" href="expmap.html" title="My Home Town"</map>
    

    <img src="kadapa_map.png" usemap="#image-map">

<map name="image-map">
    <map name="image-map">    
    
            <area target="_blank" alt="Kadapa Airport" title="Kadapa Airport" href="airport.html" coords="921,303,1163,384" shape="rect">
            <area target="_blank" alt="Ameen Peer Darga" title="Ameen Peer Draga" href="darga.html" coords="720,174,71" shape="circle">
            <area target="_blank" alt="Machupalle" title="machupalle" href="machupalle.html" coords="1095,202,1021,189,1027,87,1090,69,1147,96,1161,157,1138,194" shape="poly">
            <area target="_blank" alt="Viswanathapuram" title="Viswanathapuram" href="viswanathapuram.html" coords="930,762,1035,840" shape="rect">    
    </map>
</map>
        </center>
    </body>

</html>
```

airport.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="gray">
        <h1 align="center">
        <font color="black"><b>KADAPA</b></font>
        </h1>
        <h3 align="center">
        <font color="black"><b>Kadapa Airport</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            Kadapa Airport (IATA: CDP, ICAO: VOCP) is a domestic airport serving Kadapa (formerly Cuddapah) in Andhra Pradesh, India.
        </font>
        </p>
    </body>
</html>
```

darga.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="gray">
        <h1 align="center">
        <font color="black"><b>KADAPA</b></font>
        </h1>
        <h3 align="center">
        <font color="black"><b>Ameen Peer Darga</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            Ameen Peer Dargah in Cuddapah also known as Badi Peer Dargah is a century old mausoleum believed to fulfill wish of every pilgrim who visits the site.
        </font>
        </p>
    </body>
</html>
```
machupalle.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="gray">
        <h1 align="center">
        <font color="black"><b>KADAPA</b></font>
        </h1>
        <h3 align="center">
        <font color="black"><b>Machupalle</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            Machupalli is a Village in Sidhout Mandal in Cuddapah District of Andhra Pradesh State, India. It belongs to Rayalaseema region.
        </font>
        </p>
    </body>
</html>
```

viswanathapuram.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="gray">
        <h1 align="center">
        <font color="black"><b>KADAPA</b></font>
        </h1>
        <h3 align="center">
        <font color="black"><b>Viswanathapuram</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            It is a very good place for greenery and devotional. Which is very near to the Sri Madvirat Veera Bramendra Swamy temple
        </font>
        </p>
    </body>
</html>
```

## OUTPUT
![Screenshot 2024-10-13 183206](https://github.com/user-attachments/assets/9db1e374-8a65-40d5-a90f-3b3b4bd8bc6d)
![Screenshot 2024-10-13 183224](https://github.com/user-attachments/assets/a236b1ce-b76b-474a-93d3-4acb8221350e)
![Screenshot 2024-10-13 183303](https://github.com/user-attachments/assets/8e7f9c90-aa48-4c1b-8261-d3ed3576a869)
![Screenshot 2024-10-13 183319](https://github.com/user-attachments/assets/bcca819a-2375-46b8-9fa3-f4e7c39be7d6)


## RESULT
The program for implementing image maps using HTML is executed successfully.
