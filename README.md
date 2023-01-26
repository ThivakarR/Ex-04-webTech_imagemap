# Places Around Me
# Aim:
To develop a website to display details about the places around my house.

# Design Steps:

## Step 1
Clone the github repositry into Theia IDE.

## Step 2
Create a new Django project.

## Step 3
Write the needed HTML code.

## Step 4
Run the Django server and execute the HTML files. 

# Code:
```
map.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>HOSUR - The Little England</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Thivakar R (22003745)</b></font>
</h3>
<center>
<img src="/static/images/map1.png" border="red" width="1431" height="887" orgWidth="1431" orgHeight="887" usemap="#MyCity">
<map name="MyCity">
<area shape="rect" coords="993,14,1131,154" href="/static/html/ITpark.html/" title="IT park">
<area shape="rect" coords="831,120,903,190" href="/static/html/rto.html" title="RTO">
<area shape="rect" coords="637,779,709,831" href="/static/html/bus.html" title="Bus stand">
<area shape="rect" coords="615,723,695,775" href="/static/html/Flowermarket.html" title="Flower market">
<area shape="rect" coords="817,790,897,842" href="/static/html/Theatre.html" title="Sree Manjunatha Movie Theatre">
</map>
</center>
</body>
</html>

bus.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Bus Stand</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>HOSUR - The Little England</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Hosur Bus Stand</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b><br>About Hosur Bus Stand:</br>
    <br> </br>
In the early 1980s, the bus station was built and named after former MLA and Hosur town panchayat president Mr. K. Appavu Pillai. In 2007 due to the National Highway road expansion, the bus terminus was reconstructed, costing 6.80-10.5 crores. The new terminus was again named after Pillai and inaugurated by M. K. Stalin on 18 July 2010.
</b>
</font>
</p>
</body>
</html>

FLowermarket.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Flower Market</title>
</head>
<body bgcolor="lightgreen">
<h1 align="center">
<font color="red"><b>HOSUR - The Little England</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Hosur Flower Market</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
    <b>About Hosur Flower market:
    <br> </br>
    <br>
    There are large collection of flowers in this market.In this flower market there are mixed colors of flowers which are really amazing for decorations.we can get these flowers at low cost.
    we can find many shops in this flower market. Where people come from different places and sell their flowers in this market.when ever we go to this market we can find only fresh flowers.
    </b>
</br>
</font>
</p>
</body>
</html>

ITpark.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>IT-Park</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>HOSUR - The Little England</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Hosur IT-Park</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
    <b><br>About Hosur's IT Park:
    <br> </br>
   Applications are invited from IT/ITES Companies which have a clear roadmap for Export based business for allotment of land in the above mentioned IT Park / SEZ promoted by Government of Tamil Nadu through ELCOT (A Government of Tamil Nadu Undertaking). Electronic Manufacturing Companies with an export agenda may also apply.
ELCOT has set a standard that its IT Parks will have a six lane roads inside. The IT Parks have been designed with an international eco system such as quality housing, hotel, school, shopping mall, helipad etc.
</b>
</font>
</p>
</body>
</html>

rto.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>RTO Office</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>HOSUR - The Little England</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Hosur RTO Office</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b><br>About Hosur RTO office:
    <br> </br>
RTO office or the Regional Transport Office is a government body specifically established to oversee all transport-related operations in the country. RTOs are located throughout the country in each state and union territory. RTOs are responsible for enforcing the rules as laid down by the Motor Vehicle Act of 1988.
The department also maintains a database of all the vehicles operating in the country as well as issues licenses for drivers. Besides, the RTO office also collects road taxes, supervises pollution checks, and ensures the enforcement of all road transportation rules. If you own or drive a vehicle in India, you will need to visit the RTO to get your vehicle registered, obtain a driver’s license or renew your driver’s license, etc.
RTOs are also responsible for improving road and vehicle safety, especially to avoid accidents and other road fatalities.
</b>
</font>
</p>
</body>
</html>

theatre.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Theatre</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>HOSUR - The Little England</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Shree Manjunatha Movie Theatre</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
    <br>About Hosur's Shree Manjunatha Movie Theatre:</br>
    <br> </br>
    Manjunatha theatre located in left side service road of banglore to krishnagiri.
This theatre has two wheeler and car parking, but not a lot for car. Que system is followed to buy tickets. For every movie only 50 rupees charges. But for some 3D movies 20 extra. They maintaining moderate clean toilet. Snack and cool bar is available inside the theatre. Balcony, vip seating are available. Normal ground floor about 300 people can accomodate maximum. At balcony 200. Sound system is dts, a/c is there but not proper. Wheel chair accessible not there. Best place to bring kids, family and
Girl friends but not at rush times.
</b>
</font>
</p>
</body>
</html>
```

# Output:

![map1](https://user-images.githubusercontent.com/118348224/212536243-b0cb0496-4a3f-4669-b9f8-8c2baea78f41.png)

![dj1](https://user-images.githubusercontent.com/118707074/214842623-740fc7c3-9ee7-4431-84aa-856cd908d663.png)

![dj3](https://user-images.githubusercontent.com/118707074/214842637-11ae025f-d149-423d-bef1-d31ae02e8f39.png)

![dj4](https://user-images.githubusercontent.com/118707074/214842651-9d39d25c-05a0-493c-bff3-6fc42812d30b.png)

![dj5](https://user-images.githubusercontent.com/118707074/214842661-c3d71e69-aa39-47f8-bd01-ac6eaf3a0d29.png)

![dj6](https://user-images.githubusercontent.com/118707074/214842672-c8d2c652-fd64-4066-9722-67fb4562caf4.png)


# Result:

Thus, The program for implementing image map is executed successfully.
