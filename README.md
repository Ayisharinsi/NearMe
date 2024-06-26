# Ex04 Places Around Me
## Date:22-03-2024

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
    <!DOCTYPE html>
<html lang="en">
<head>
<title>NATIVE PLACE</title>
</head>
<body>
<h1 align="center">
<font color="black"><b>KERALA</b></font>
</h1>
<h3 align="center">
<font color="purple"><b>AYISHA RINSI K (212223040022)</b></font>
</h3>
<center>
<img src="kerala.png" usemap="#kerala" >
<map name="kerala">

<area shape="rectangle" coords="881,200,1060,279" href="hillpalace.html"  title="HILL PALACE MUSEUM">
<area shape="rectangle" coords="1104,498,1303,559" href="KOCHAREEKKALCAVES.html" title="KOCHAREEKKAL CAVES">
<area shape="rectangle" coords="1095,583,1253,705" href="AREEKAL WATERFALLS.html" title="AREEKAL WATERFALLS">
<area shape="rectangle" coords="912,535,1106,604" href="TIST.html" title=" TIST">
<area shape="rectangle" coords="649,303,837,423" href="WONDERLA AMUSEMENT.html" title="WONDERLA AMUSEMENT">
</map>
</center>
</body>
</html>

hillpalace.html
    <head>
        <title>HILL PALACE MUSEUM</title>
    </head>
    <body bgcolor="pink">
    <h1 align="center">
    <font color="black"><b>KERALA</b></font>
    </h1>
    <h3 align="center">
    <font color="purple"><b>HILL PALACE MUSEUM</b></font>
    </h3>
    <hr size="3" color="white">
    <p align="justify">
    <font face="Georgia" size="5">
    The Hill Palace Museum in Kerala, once the Kochi royal residence, is the state's largest archaeological museum. Built in 1865, it blends traditional Kerala and colonial architecture. With vast collections including artifacts, antiques, and manuscripts, it offers insights into Kerala's cultural heritage. A popular tourist destination, it showcases Kerala's rich history and culture.
    </p>
    </body>
</html>

WONDERLA AMUSEMENT.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>WONDERLA AMUSEMENT</title>
</head>
<body bgcolor="gray">
<h1 align="center">
<font color="black"><b>KERALA</b></font>
</h1>
<h3 align="center">
<font color="purple"><b>WONDERLA AMUSEMENT</b></font>
</h3>
<hr size="3" color="white">
<p align="justify">
<font face="Georgia" size="5">
Wonderla Amusement Park in Kerala, situated in Kochi, is a renowned destination for entertainment and adventure. Boasting a variety of exhilarating rides, water attractions, and entertainment shows, Wonderla offers fun experiences for visitors of all ages. It is a popular spot for families and thrill-seekers alike in the state of Kerala.
</p>
</body>
</html>

TIST.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>TIST</title>
</head>
<body bgcolor="green">
<h1 align="center">
<font color="black"><b>KERALA</b></font>
</h1>
<h3 align="center">
<font color="purple"><b>TIST</b></font>
</h3>
<hr size="3" color="white">
<p align="justify">
<font face="Arial" size="5">
TIST, or Thunchaththu Ezhuthachan Malayalam University Institute of Science and Technology, is located in Kerala, India. It focuses on research and education in science and technology, with a special emphasis on Malayalam language and culture. Offering undergraduate and postgraduate programs, TIST promotes scientific education and research within Kerala.
</p>
</body>
</html>

KOCHAREEKKALCAVES.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>KOCHAREEKKAL CAVES</title>
</head>
<body bgcolor="brown">
<h1 align="center">
<font color="black"><b>KERALA</b></font>
</h1>
<h3 align="center">
<font color="purple"><b>KOCHAREEKKAL CAVES</b></font>
</h3>
<hr size="3" color="white">
<p align="justify">
<font face="Tahoma" size="5">
The Kochareekkal Caves, also known as Edakkal Caves, in Wayanad district, Kerala, feature ancient petroglyphs dating back over 8,000 years. These rock engravings depict scenes of humans, animals, and symbols, offering insights into prehistoric civilization. Accessible by trekking up Ambukuthi Hills, the caves are a significant archaeological site.
 </p>
</body>
</html>

AREEKAL WATERFALLS.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>AREEKAL WATERFALLS</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="black"><b>KERALA</b></font>
</h1>
<h3 align="center">
<font color="purple"><b>AREEKAL WATERFALLS</b></font>
</h3>
<hr size="3" color="white">
<p align="justify">
<font face="Courier New" size="5">
 However, there are several magnificent waterfalls in Kerala that attract visitors with their natural beauty and charm. Some of the most famous waterfalls in Kerala include Athirappilly Falls, Vazhachal Falls, Meenmutty Falls, and Soochipara Falls. These waterfalls are nestled amidst lush greenery and offer breathtaking views, making them popular destinations for nature lovers and tourists visiting Kerala
</p>
</body>
</html>
```
## OUTPUT
![kerala1](https://github.com/Ayisharinsi/NearMe/assets/148609304/9fa0dd4c-8dc7-48a0-82f5-1d526abc8f98)
![kerala2](https://github.com/Ayisharinsi/NearMe/assets/148609304/cedb358d-3c1d-4b44-b9c2-270a96a59c80)
![kerala3](https://github.com/Ayisharinsi/NearMe/assets/148609304/25668cbb-3743-41d6-af37-f13839a4918b)
![kerala4](https://github.com/Ayisharinsi/NearMe/assets/148609304/6d564e19-0b63-482f-94d2-c1ed4d5bc8ec)
![KERALA5](https://github.com/Ayisharinsi/NearMe/assets/148609304/8e165b5e-ceda-451e-b1c2-533987799af3)
![kerala6](https://github.com/Ayisharinsi/NearMe/assets/148609304/5838c075-1632-4cb0-bc8c-833cee75c6af)



## RESULT
The program for implementing image maps using HTML is executed successfully.
