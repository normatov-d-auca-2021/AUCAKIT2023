<!DOCTYPE html>
<html lang= "en">

<head>
    <meta name="viewport" content="with=device-width, initial-scale = 1.0">
    <title>Website about Tajikistan</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Croissant+One&family=Kanit:ital,wght@1,300&display=swap" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
</head>

<body>  
    <section class="headerOfWebSite" style="min-height: 100vh; width: 100%; background-image: linear-gradient(rgba(4,9,30,0.7), rgba(4,9,30,0.7)), url('222.jpg'); background-position: center; background-size: cover; position: relative;"> 
        <nav>
            <img src="Mountain-logo-template-on-transparent-background-PNG.png">
            <div class="navigationLinks" id="navLinks">
                <i class="fa fa-times" onclick="hideMenu() "></i>
                    <ul>
                        <li><a href="">HOME</a></li>
                        <li><a href="tours">TOURS</a></li>
                        <li><a href="https://github.com/normatov-d-auca-2021/webpagefall2023/blob/main/goals.md">GOALS</a></li>
                        <li><a href="food">FOOD</a></li>
                        <li><a href="culture">CULTURE</a></li>
                    </ul>
            </div>
            <i class="fa fa-bars" onclick="showMenu()"></i>
        </nav>

    <div class="textsBox">

        <h1>Welcome to Tajikistan</h1>
        <p>Tajikistan is a country in Central Asia consisting of 93% of mountains.<br> 
            It has 4 regions: Badakhshan, Khatlon, Sughd and Regions of Republician Subordinations.<br> 
            Our touristic company provides tours to the different parts of Tajikitsan. 
            Our tours varies from one-day to three-days tours.
             <br>It’s known for rugged mountains, popular for hiking and climbing. </p>
    <a href="" class="btn">Explore To Know More</a>
    </div>

    </section>

    <section class="TOURSEWEOFFER">
        <h2>TOURS WE OFFER</h2>
        <p>Tajikistan is full of touristic experiences. 
        You can feel everything including the variety of intertainments</p>

        <div class = "row">
            <div class ="placecol">
                <h3>ONE-DAY TOUR</h3>
                <p>Savor the essence of Tajikistan in just one day. Our 1-day tours are designed for a 
                    quick yet immersive adventure, where you can explore historical sites, enjoy local flavors, and experience the 
                    vibrant culture of Tajikistan. Join us for a day of discovery in this hidden gem of Central Asia.</p>
            </div>

            <div class ="placecol">
                <h3>TWO-DAY TOUR</h3>
                <p>Our 2-day tours in Tajikistan offer you an extended opportunity to delve deeper into this captivating land.
                    With an extra day, you can fully immerse yourself in Tajikistan's rich culture and breathtaking landscapes.</p>
            </div>

            <div class ="placecol">
                <h3>THREE-DAY TOUR</h3>
                <p>Our 3-day tours in Tajikistan offer you an extended opportunity to delve deeper into this captivating land. 
                    With an extra day, you can fully immerse yourself in Tajikistan's rich culture and breathtaking landscapes.</p>
            </div>
        </div>
    </section>

    <!-------TO VISIT ------->
    <section class = "tovisit">
        <h1>TOP-3 PLACES YOU CAN VISIT</h1>
        <p>Here you can find TOP-3 cities in Tajikistan that must be visited. They are full of cultural and historical places.</p>

        <div class="row">
            <div class="tovisit-col">
                <img src="стела.jpg">
                <div class="layer">
                    <h3>DUSHANBE</h3>
                </div>
            </div>

            <div class="tovisit-col">
                <img src="Iskanderkul-Lake-Tajikistan-Fann-Mountains-3.jpg">
                <div class="layer">
                    <h3>ISKANDERKUL</h3>
                </div>
            </div>

            <div class="tovisit-col">
                <img src="Edited-Pamir-Highway-1024x672.jpg">
                <div class="layer">
                    <h3>PAMIR HIGHWAY</h3>
                </div>
            </div>
        </div>
    </section>

    <section class="experience">
        <h1>Our Experience</h1>
        <p>.</p>

        <div class="row">
            <div class="experience-col" style="display: flex; align-items: center;">
                <div style="flex: 50%;">
                    <img src="exp1.jpeg" style="width: 100%;">
                </div>
                <div style="flex: 50%;">
                    <!-- Add your text here -->
                    <p style="font-size: 20px;">This is Josh, he is our first client who experienced travelling towards the north side - Khujand City. He also experienced trabelling to the small villages around the city</p>
                </div>
            </div>
        </div>

        <div class="row">
            <div class="experience-col" style="display: flex; align-items: center;">
                <div style="flex: 1; max-width: 50%;">
                    <!-- Text here -->
                    <p style="font-size: 20px;">This is Jessica, she is our  client who experienced travelling during the 3-day tour towards the east side - Pamir. She experienced the living in the mountatins and tried our national food like Qurutob, Osh, Shurbo.</p>
                </div>
                <div style="flex: 1; max-width: 50%;">
                    <!-- Image here -->
                    <img src="exp2.webp" style="width: 100%; height: auto;">
                </div>
            </div>
        </div>

        <div class="row">
            <div class="experience-col" style="display: flex; align-items: center;">
                <div style="flex: 50%;">
                    <img src="exp3.jpeg" style="width: 100%;">
                </div>
                <div style="flex: 50%;">
                    <!-- Add your text here -->
                    <p style="font-size: 20px;">These people are the travellers from Norway. We showed them the beauties of our nature during 2-days spending in Kulob City, and the closest villages</p>
                </div>
            </div>
        </div>
        

         
    </section>

</body>

<script>
    var navLinks = document.getElementById("navLinks");

        function showMenu(){
            navLinks.style.right = "0";
        }
        function hideMenu(){
            navLinks.style.right = "-200px";
        }
</script>

</html>

<!--------CSS FILE-------->

<style>

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Kanit', sans-serif;
}

nav{
    display: flex;
    padding: 0% 2%;
    justify-content: space-between;
    align-items: center;
}

nav img{
    width: 150px;
}

.navigationLinks{
    flex: 1;
    text-align: right;
}

.navigationLinks ul li{
    list-style: none;
    display: inline-block;
    padding: 8px 12px;
    position: relative;
}

.navigationLinks ul li a{
    color: #fff;
    text-decoration: none;
    font-size: 17px;
}

.navigationLinks ul li::after{
    content: '';
    width: 0%;
    height: 3px;
    background: #87CEEB;
    display: block;
    margin: auto;
    transition: 0.5s ;
}

.navigationLinks ul li:hover::after{
    width: 100%; 
}

.navigationLinks ul li:first-child{
   margin-left: 0;
}

.textsBox{
    width: 90%;
    color: #fff;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
}

.textsBox h1{
    font-size: 62px;
}

.textsBox p{
    margin: 10px 0 40px;
    font-size: 14px;
    color: #fff;
}

.btn{
    display: inline-block;
    text-decoration: none;
    color: #fff;
    border: 1px solid #fff;
    padding: 12px 34px;
    font-size: 13px;
    background: transparent;
    position: relative;
    cursor: pointer;
}

.btn:hover{
    border: 1px solid #87CEEB;
    background: #87CEEB;
    transition: 1s;
}

nav .fa{
    display: none;
}

@media(max-width: 700px)
{
    .row{
        flex-direction: column;
    }

    .tovisit-col{
        width: 100%;
        margin-bottom: 20px;
    }

    .textsBox h1{
        font-size: 30px;
    }

    .navigationLinks ul li{
        display: block;
    }
    .navigationLinks{
        position: absolute;
        background: #87CEEB;
        height: 100vh;
        width: 200px;
        top: 0;
        right: -200px;
        z-index: 2;
        transition: 0.5s;
    }

    nav .fa{
        display: block;
        color:#fff;
        margin: 10px;
        font-size: 22px;
        cursor: pointer;
    }

    .navigationLinks ul{
        padding: 30px;
    }

}

.TOURSEWEOFFER{
    width: 80%;
    margin: auto;
    text-align: center;
    padding-top: 100px;
}
h1{
    font-size: 36px;
    font-weight: 600;
}

p{
    color: #403f3f;
    font-size: 14px;
    font-weight: 300;
    line-height: 22px;
    padding: 10px;
}

.row{
    margin-top: 5%;
    display: flex;
    justify-content: space-between;
}

.placecol{
    flex-basis: 31%;
    background:  #9dd2e7;
    border-radius: 10px;
    margin-bottom: 5%;
    padding: 20px 12px;
    box-sizing: border-box;
    transition: 0.5s;  
}

h3{
    text-align: center;
    font-weight: 600;
    margin: 10px 0;
}

.placecol:hover{
    box-shadow: 0 0 20px 0px rgba(0, 0, 0, 2);
}

.tovisit{
    width: 80%;
    margin: auto;
    text-align: center;
    padding-top: 50px;
}

.tovisit-col {
    flex-basis: 32%;
    border-radius: 10px;
    margin-bottom: 30px;
    position: relative;
    overflow: hidden;
}

.tovisit-col img {
    width: 100%;
    height: 90%;
    display: block;
}


.layer {
    background: transparent;
    height: 90%;
    width: 100%;
    position: absolute;
    top: 0;
    left: 0;
    transition: 0.5s;
    text-align: right; 
}

.layer:hover {
    background: rgba(135, 206, 235, 0.7);
}

.layer h3{
    width: 100%;
    font-weight: 500;
    color: #fff;
    font-size: 26px;
    bottom: 0;
    left: 50%;
    transform: translateX(-50%);
    position: absolute;
    opacity: 0; 
    transition: 0.5s;
}

.layer:hover h3{
    bottom: 49%;
    opacity: 1;
}

/*-------FACILITIES-------*/

.experience{
    width: 80%;
    margin: auto;
    text-align: center;
    padding-top: 100px; 
}

</style>