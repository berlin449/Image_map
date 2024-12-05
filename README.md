# Ex04 Places Around Me
# Date:
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE :
```
<html>
   <head>
        <title>image map</title>
</head>

   <body><center>
    <img src="C:\Users\navee_2o7x4uh\OneDrive\Desktop\HTML\images\map.shakthi02.JPG" alt="Sample Image" usemap="#my-map" class="image-map" width="800px" height="680px">
<map name="my-map">
        <area shape="rect" coords="50,50,150,150" href="file:///C:/Users/navee_2o7x4uh/OneDrive/Desktop/HTML/map%20areas/chola.html" alt="Area 1">
        <area shape="circle" coords="300,200,50" href="file:///C:/Users/navee_2o7x4uh/OneDrive/Desktop/HTML/Restuarent/hotal.html" alt="Area 2">
        <area shape="poly" coords="400,50,450,100,400,150,350,100" href="file:///C:/Users/navee_2o7x4uh/OneDrive/Desktop/HTML/map%20areas/thanjai.html" alt="Area 3">
        <area shape="poly6" coords="637,314,681,352,717,322,678,286" href="file:///C:/Users/navee_2o7x4uh/OneDrive/Desktop/HTML/map%20areas/madurai.html" alt="Area 4">
        <area shape="rect" coords="129,340,179,380" href="file:///C:/Users/navee_2o7x4uh/OneDrive/Desktop/HTML/map%20areas/church.html" alt="Area 5">
      </map></center> 
</body>
</html>


<html>
    <head>
        <title>area1</title>
    </head>
    <body><center>
        <h1>KANGAI KONDA CHOZHA PURAM</h1>
        <img src="https://media.istockphoto.com/id/1205243298/photo/the-beautiful-gangaikonda-cholapuram-temple-dedicated-to-lord-shiva-in-tanjore-tamil-nadu.jpg?s=612x612&w=0&k=20&c=2KqCHtddlP1HPBN_ih31FEVRcEW7fuqwDwUR5mQJTpk=" alt="cholapuram" width="400px" height="400px">
    <p style="font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif ; font-size: larger;">Kangai Konda Chola Puram, also known as Kanchi Konda Chola Puram, is a historic town in Tamil Nadu, India, known for its association with the Chola dynasty. This town is significant as it was established by the great Chola ruler, Raja Raja Chola I, during his reign in the 11th century. It served as the capital of the Chola Empire for a period and played a pivotal role in the region’s political and cultural history.</p>
    <p style="font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif ; font-size: larger;">The name Kangai Konda Chola Puram translates to "The city of the Chola who conquered the Konga region," referring to Raja Raja Chola I's military campaigns. The town is located near the present-day Kanchipuram, and it became a symbol of Chola's might and grandeur.</p>
    <p style="font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; font-size: larger;">The town is home to the Kangai Konda Chola Temple, a testament to the architectural brilliance of the Chola period. This temple, along with the nearby Brihadeeswarar Temple in Thanjavur, showcases the Chola dynasty's expertise in temple construction, with intricate carvings and vast courtyards. Kangai Konda Chola Puram also became a center for religious and cultural activities, contributing significantly to Tamil art, architecture, and literature.</p>
</body></center>
</html>


<html>
    <head>
        <title>Thanjai</title>
    </head>
    <body><center>
        <h1>THANJAI PERIYA KOVIL</h1>
    <img src="https://i.pinimg.com/736x/c2/a4/1f/c2a41f933a33ea3c9ff512db6d2d76bc.jpg" alt="Thanjai" width="400px" height="400px">
    <p style="font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; font-size: larger;">Tanjai Periya Kovil, also known as the Brihadeeswarar Temple, is one of the most iconic and grandiose architectural marvels of ancient South India, located in Thanjavur, Tamil Nadu. This magnificent temple was built by the great Chola king Raja Raja Chola I in the early 11th century, around 1010 AD, and stands as a testament to the architectural brilliance and cultural grandeur of the Chola dynasty.</p>
    <p style="font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; font-size: larger;">The Brihadeeswarar Temple is dedicated to Lord Shiva, and it is one of the largest temples in India. It is an outstanding example of Dravidian architecture, with intricate sculptures, expansive courtyards, and towering gopurams (gateway towers). The temple's main sanctum houses a massive Shiva lingam, symbolizing the deity, and the vimana (tower) over the sanctum rises to about 66 meters, making it one of the tallest of its kind in India.</p>
    <p style="font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; font-size: larger;">The temple's artwork and carvings depict various mythological stories and scenes from Hindu scriptures, showcasing the creativity and craftsmanship of the artisans of the time. The structure is made of granite, which was transported from nearby quarries, highlighting the Chola dynasty's engineering prowess.</p>
    <p style="font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; font-size: larger;">A UNESCO World Heritage Site, the Brihadeeswarar Temple continues to draw pilgrims, historians, and tourists, not only for its spiritual significance but also as a symbol of the rich cultural legacy of the Chola Empire.</p>
</body></center>
</html>



<html>
    <head>
        <title>madurai</title>
    </head>
    <body><center>
        <h1>MADURAI MEENAKSHI AMMAN TEMPLE</h1>
        <img src="https://live.staticflickr.com/8539/8603663088_618a4ea76c_b.jpg" alt="madurai" width="420px" height="370px">
         <p style="font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif; font-size: larger;">The Madurai Meenakshi Amman Temple, located in the heart of Madurai, Tamil Nadu, is one of India’s most celebrated and iconic temples. Dedicated to Goddess Meenakshi, a form of Parvati, and her consort, Lord Sundareswarar (Shiva), the temple symbolizes the spiritual and cultural heritage of South India. With its origins tracing back to ancient Tamil Sangam literature, the temple has stood as a beacon of devotion, art, and architecture for centuries.

            The temple complex spans over 15 acres and is renowned for its towering gopurams (gateway towers), intricately adorned with thousands of colorful sculptures depicting deities, mythical creatures, and scenes from Hindu epics. The tallest gopuram, soaring to a height of 170 feet, is a testament to the grandeur of Dravidian architecture. Inside, the halls and sanctums are equally mesmerizing, with the Thousand Pillar Hall (Aayiram Kaal Mandapam) standing out for its exquisite carvings and symmetry.</p>
          <p style="font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif; font-size: larger;"> The central sanctum houses the idol of Goddess Meenakshi, depicted with a parrot and a lotus, radiating divine grace. Her union with Lord Sundareswarar is celebrated annually during the vibrant Chithirai Festival, attracting millions of devotees and tourists from around the globe.

            The temple is not just a religious site but also a cultural hub. It hosts daily rituals, classical music, and dance performances that echo the timeless traditions of Tamil Nadu. Its architectural precision, spiritual significance, and artistic brilliance make it a UNESCO World Heritage contender and a must-visit destination.
            
            The Madurai Meenakshi Amman Temple continues to inspire awe, embodying the enduring legacy of devotion and creativity that defines the soul of Tamil culture.</p>  
            
            
            

    </body></center>
</html>



<html>
    <head>
        <title>church</title>
    </head>
    <body><center>
    <h1>VELANKANNI CHURCH</h1>
    <img src="https://vailankannihotels.com/shrinebasilica/homefade/1.jpg" alt="church" width="430px" height="350px">
    <p style="font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; font-size:x-large ;">
        The Velankanni Church, also known as the Basilica of Our Lady of Good Health, is a renowned Roman Catholic shrine located in Velankanni, Tamil Nadu. Situated along the Coromandel Coast, this sacred site is often referred to as the "Lourdes of the East" due to its reputation for miraculous healings and its global significance as a pilgrimage center.
        
        The church’s origins date back to the 16th century and are rooted in local legends of miraculous events involving the Virgin Mary. Over the centuries, it has evolved into an architectural marvel with Gothic-style design and pristine white facades, exuding serenity and grace.</p>
    <p  style="font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; font-size:x-large ;"> The church is a symbol of unity and faith, attracting devotees from various religions and regions. The annual Feast of Our Lady of Good Health, celebrated in September, is a grand event drawing millions of pilgrims who come to offer prayers and gratitude. The nine-day festival is marked by processions, special masses, and vibrant cultural displays.

        Velankanni Church is more than a religious site; it is a haven of hope and solace. Its peaceful ambiance, coupled with its spiritual significance, makes it a cherished destination for people seeking divine blessings and inner peace.</p>
    </body></center>
</html>



<!DOCTYPE html>
<html>
    <head>
        <title>THE HUNGRY BITE</title>
        <style>
             body{
                background-size: 1550px;
                background-image: url(https://img.freepik.com/premium-photo/high-angle-view-tomatoes-cilantro-by-herb-bottle-black-table_1048944-22848081.jpg);
                background-position: center;
                background-repeat: no-repeat;

            }
            .image-row{
                    display: flex;
                    gap: 1.3%;
                }
                .image-row img{
                    width: 170PX;
                    height: 180PX;

                }
        </style>
            </head>
    <center>
    <body>
        <h1 style="color: antiquewhite;">THE HUNGRY Bites</h1>
        <h2 style="color: gray;">Welcome to HUNGRY Bites!</h2>
        <h3 style="color: blanchedalmond;"></h3>
        <nav>
            <ul>
                <hr><a href="https://www.zomato.com/chennai/order-food-online" style="color: bisque; size: 10px;" >ORDER</a>------
                <a href="C:\Users\navee_2o7x4uh\OneDrive\Desktop\HTML\Naveen.html" style="color: aqua;">MENU</a>------
                <a href="C:\Users\navee_2o7x4uh\OneDrive\Desktop\HTML\Restuarent\admin.html">ABOUT</a><hr>

            </ul>
        </nav>
        <style>
           
        </style>
        <br>
        <br>
        <br>
        <br>
        <div  class="image-row">
             <div>
                <br><br><p><B style="color: antiquewhite;">01.CHICKEN TIKKA</B></p>
                <p style="color: bisque;">(Chicken Tikka are boneless pieces of chicken)</p>
            </div>
          <BR><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRDuxOXxEoeV_2GfnqwVVkt1ffDmbGotRPAxQ&s">
           
            <div>
                <br><br><p><b style="color: antiquewhite;">02.GRILLED CHICKEN</b></p>
                <p style="color: bisque;">(This recipe guarantees juicy, flavorful chicken every time.)</p>
            </div>
            <img src="https://www.budgetbytes.com/wp-content/uploads/2024/06/Grilled-Chicken-Overhead.jpg">
            <div>
                <br><br><p style="color: rgb(236, 227, 236);"><b>03.SEAFOOD PEALLA</b></p>
                <p style="color: bisque;">(clams, mussels and shrimp along with smoky chorizo and saffron)</p>
            </div>
            <img src="https://www.fourtocookfor.com/wp-content/uploads/2020/05/seafood-paella-16-500x500.jpg">
            <div>
                <br><br><p style="color: rgb(238, 200, 200);">04.CHICKEN WINGS</p>
                <p style="color: bisque;">(super crispy Baked Chicken Wings!)</p>
            </div>
            <img src="https://images.getrecipekit.com/20240103192542-buffalo-chicken-wings.jpg?aspect_ratio=4:3&quality=90&">
            
            </div>
            <br>
            <br>
            <h3 style="color: bisque;">The Perfect Bite, Every Time</h3>
            <h4 style="color: bisque;">THANK YOU, Visit Again...</h4>
            <br>
        </center>
        <p style="color: bisque;"><b>To Contact us visit our website : Hungry bites.in </b></p>
        <p style="color: bisque;"><b>T.Nagar,chennai-600029.</b></p>
        <p style="color: brown;"><B>copyright@HUNGRY Bites...</B></p>

    </body>
</html>

```
# OUTPUT :
# Image Map:
![Screenshot (23)](https://github.com/user-attachments/assets/1c0142c4-e52a-45eb-ae2e-a49d97bdacdc)
# Kangai Konda Chozhapuram :
![Screenshot (24)](https://github.com/user-attachments/assets/e60144c9-41ee-4c83-80bd-832ef4490724)


# Thanjai Periya Kovil :
![Screenshot (25)](https://github.com/user-attachments/assets/1796c382-13dd-4e71-84d9-1dc17e79a62c)
# Meenakshi Amman Temple :
![Screenshot (27)](https://github.com/user-attachments/assets/c28cc3fe-93b2-412c-9cbe-628db68687c2)
# Velankanni Church :
![Screenshot (26)](https://github.com/user-attachments/assets/5c08542b-0ee3-477d-8dee-40ff07297aa1)\
# My Restuarent Wesite :
![Screenshot (28)](https://github.com/user-attachments/assets/8b697a88-9e28-4dc4-b837-2224176c8e13)







# RESULT
The program for implementing image maps using HTML is executed successfully.
