# Ex04 Places Around Me
## Date: 24:03:2024

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
<head>
    <title>MY CITY</title>
    <link rel="icon" href="WIN_20231003_09_51_15_Pro.jpg">

</head>
<body>
<center>
<h2>
    <font color="red">GINGEE...  </font></h2>
        <h3><font color="blue">Madhanraj(23013616)</font> </h3>
  
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="500,250,600,300" href="bus.html" title="Bus stand">
<area shape="circle" coords="330,410,50" href="mob.html" title="Poorvika Mobiles">
<area shape="circle" coords="920,410,50" href="sch.html" title="Chanakaya Matric.hr.sec.school.">
<area shape="circle" coords="950,550,40" href="hos.html" title="Government Hospital">
<area shape="circle" coords="730,110,40" href="cin.html" title="Saravan Cine Plex">
</center>
</body>
</html>

bus.html
<!DOCTYPE html>
<html lang="en">
<head  >
    <title>MY CITY</title>
    <link rel="icon" href="WIN_20231003_09_51_15_Pro.jpg">

</head>
<body bgcolor="yellow">
<center>
<h1 >
    <font color="blue">GINGEE</font></h1>
    <h2>
        <font color="red">🚌  Bus stand 🚏</font></h2>
        <hr size="3" color="purple">
<p align="justify"> Gingee Bus Stand Overview The Gingee Bus Stand is a bus station located in Gingee, Villupuram, Tamil Nadu, India. It is situated near the Saravana theater and Suriya Hospital. 

    Bus Services The Gingee Bus Stand offers bus services to various destinations within Tamil Nadu and neighboring states. It is a convenient transportation hub for both local and long-distance travel. 
    
     Amenities The Gingee Bus Stand provides basic amenities for passengers, including waiting areas, restrooms, and ticket counters. It is also located near several shops and restaurants, offering convenience to travelers. </p>        
</body>
</html>

cin.html
<!DOCTYPE html>
<html lang="en">
<head  >
    <title>MY CITY</title>
    <link rel="icon" href="WIN_20231003_09_51_15_Pro.jpg">

</head>
<body bgcolor="pink">
<center>
<h1 >
    <font color="red">GINGEE</font></h1>
    <h2>
        <font color="brown">🎥 Saravana Cinema 🎬</font></h2>
        <hr size="3" color="lightblue">
        <p align="justify"> About Saravana Cinema in Gingee Saravana Cinema is a popular movie theatre located in Gingee, India. It is known for screening Tamil movies and is a popular destination for moviegoers in the area. 

            Saravana Cinema's Offerings The cinema offers a variety of amenities to enhance the movie-going experience, including comfortable seating, a large screen, and a state-of-the-art sound system. It also has a concession stand that sells snacks and drinks. 
            
            Popular Movies at Saravana Cinema Saravana Cinema screens a wide range of Tamil movies, including both new releases and classic films. Some of the most popular movies that have been screened at the cinema include "Master," "Karnan," and "Soorarai Pottru." </p>  
</body>
</html>

hos.html
<!DOCTYPE html>
<html lang="en">
<head  >
    <title>MY CITY</title>
    <link rel="icon" href="WIN_20231003_09_51_15_Pro.jpg">

</head>
<body bgcolor="cyen">
<center>
<h1 >
    <font color="brown">GINGEE</font></h1>
    <h2>
        <font color="purple">🚑Government Hospital 👩‍⚕️ </font></h2>
        <hr size="3" color="green">
        <p align="justify">Government Hospital Gingee Overview: Government Hospital Gingee is a Taluk Hospital located in Gingee, which provides various medical services. You can contact them at 04145-222015 or email at  

            Emergency Services at Government Hospital Gingee: The hospital is known for providing timely intensive care to patients and offers various emergency services. You can reach out to them for more information on the services available. 
            
            Government Primary Health Center in Gingee: Situated at Tiruvannamalai Road, Sathiyamangalam, Bazaar-604202, the Government Primary Health Center is easily accessible and provides healthcare services to the local communit</p>    
</body>
</html>

mob.html
<!DOCTYPE html>
<html lang="en">
<head  >
    <title>MY CITY</title>
    <link rel="icon" href="WIN_20231003_09_51_15_Pro.jpg">

</head>
<body bgcolor="pink">
<center>
<h1 >
    <font color="brown">GINGEE</font></h1>
    <h2>
        <font color="green">📱 Poorvika Mobiles 🛒 </font></h2>
        <hr size="3" color="orange">
        <p align="justify">Poorvika Mobiles in Gingee Poorvika Mobiles Pvt Ltd is a leading mobile phone dealer in Gingee, India. They offer a wide range of smartphones, accessories, and gadgets from top brands. 

            Poorvika Mobiles Online You can also shop for Poorvika Mobiles products online at their website. They offer a variety of payment options and deliver to all major cities in India. 
            
             Poorvika Mobiles Contact Information To contact Poorvika Mobiles in Gingee, you can call them at +91 99944 44441 or visit their store at Near Surya Super Market, Villupuram Salai, Gingee Bazaar, Gingee.</p>    
</body>
</html>

sch.html
<!DOCTYPE html>
<html lang="en">
<head  >
    <title>MY CITY</title>
    <link rel="icon" href="WIN_20231003_09_51_15_Pro.jpg">

</head>
<body bgcolor="orange">
<center>
<h1 >
    <font color="purple">GINGEE</font></h1>
    <h2>
        <font color="red">🏫 Chanayaka matric.hr.sec.school📚</font></h2>
        <hr size="3" color="cyen">
        <p align="justify">
        Chanakya Matric School Overview Chanakya Matric Higher Secondary School is a co-educational school located in Gingee, Viluppuram district of Tamil Nadu, India. It offers education from grades 1 to 12 and has a team of 44 dedicated and professional teachers. 

 Educational Approach The school aims to provide excellence in education through well-educated and trained governance. Apart from academic proficiency, it also focuses on co-curricular and extra-curricular activities. 

 School Infrastructure Chanakya Matric Higher Secondary School has a well-developed infrastructure, including classrooms, a library, a computer lab, and a playground. It also provides transportation facilities for students. 
        </p>           
</body>
</html>
```

## OUTPUT
![Screenshot (14)](https://github.com/madhanraj67/NearMe/assets/150319515/ed167a25-74ee-4946-8a92-dcad57ccb004)
![Screenshot (15)](https://github.com/madhanraj67/NearMe/assets/150319515/537bff80-2199-413c-b5e6-e4b8005512a1)
![Screenshot (16)](https://github.com/madhanraj67/NearMe/assets/150319515/cf44c385-5018-4f2e-92a8-8d79a72601f5)
![Screenshot (17)](https://github.com/madhanraj67/NearMe/assets/150319515/2348cbc6-f43f-468c-afe3-aaff4b83209e)
![Screenshot (18)](https://github.com/madhanraj67/NearMe/assets/150319515/0a0b12dc-4b48-4981-9512-4dade76e4891)
![Screenshot (19)](https://github.com/madhanraj67/NearMe/assets/150319515/5eab9b54-ee0e-404d-83ae-cb3e31803136)












## RESULT
The program for implementing image maps using HTML is executed successfully.
