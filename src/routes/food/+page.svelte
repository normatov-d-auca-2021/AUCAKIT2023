<!DOCTYPE html>
<html lang="en">
<head>
    <title>FOOD</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Croissant+One&family=Kanit:ital,wght@1,300&display=swap" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
</head>
<body style="background-image: url('fd1.jpeg'); background-size: cover; background-position: center; margin: 0; font-family: 'Kanit', sans-serif; color: rgb(255, 255, 255);">
    <div class="content-overlay">
        <header>
            <!-- Navigation bar -->
            <!-- Add your navigation bar here -->
        </header>

        <section class="welcome-section">
            <div class="welcome-content">
                <h1>FOOD</h1>
                <p>Explore the rich and vibrant diversity of food in Tajikistan.</p>
                <div class="food-row">
                    <div class="place-col">
                        <img src="plov.jpeg">
                        <h3>Tajik Osh</h3>
                    </div>

                    <div class="place-col">
                        <img src="mantu.jpeg">
                        <h3>Traditional Mantu</h3>
                    </div>

                    <div class="place-col">
                        <img src="kurutob.jpeg">
                        <h3>National Kurutob</h3>
                    </div>
                </div>








            </div>
        </section>

        <section class="food">
            <h1>Places to Eat Food</h1>

            <div class="row">
                <div class="food-col">
                    <img src="fd444.jpeg">
                    <h3>Shomi Kulob</h3>
                    <p>In the heart of Tajikistan, you can try the best Mantu, Kurutob, Osh, Shakarob.</p>
                </div>

                <div class="food-col">
                    <img src="fd333.jpeg">
                    <h3>Oshi Bunavsha</h3>
                    <p>You can try our special Osh in the place called Oshi Bunavsha</p>
                </div>

                <div class="food-col">
                    <img src="fd222.jpeg">
                    <h3>Antient Tajik</h3>
                </div>
            </div>
        </section>
    </div>
</body>
</html>

<style>
    .content-overlay {
        background: rgba(30, 30, 30, 0.64); /* Dark transparent overlay */
        padding: 20px;
    }

    .welcome-section {
        text-align: center;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: flex-start;
    }

    .welcome-content {
        z-index: 2;
        padding-top: 20px;
    }

    .welcome-section h1, .food h1 {
        font-family: 'Croissant One', cursive;
        font-size: 48px;
        margin-bottom: 20px;
    }

    .welcome-section p {
        font-size: 30px;
    }

    .food {
        width: 80%;
        margin: auto;
        text-align: center;
        padding-top: 100px;
    }

    .food h1 {
        color: white; /* Adjusted for visibility */
        font-size: 50px;
    }

    .row {
        display: flex;
        justify-content: space-around;
        flex-wrap: wrap;
    }

    .food-col {
        flex-basis: 30%; /* Adjust this value as needed */
        margin: 10px;
        border-radius: 10px;
        text-align: center; /* Center align the content */
        height: 30%;
    }

    .food-col img {
        width: 100%; 
        height: 80%;
        border-radius: 10px;
        margin-bottom: 15px; /* Space between image and text */
    }

    .place-col {
        flex-basis: 30%; /* Adjust this value as needed */
        margin: 10px;
        border-radius: 10px;
        text-align: center; /* Center align the content */
    }

    .place-col img {
        width: 100%; /* Adjust image width to fit the container */
        border-radius: 10px;
        margin-bottom: 15px; /* Space between image and text */
    }
    
    .food-row{
        display: flex;
        justify-content: space-around;
        flex-wrap: wrap;
    }
</style>

