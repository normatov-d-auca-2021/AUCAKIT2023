<!DOCTYPE html>
<html lang="en">
<head>
    <title>CULTURE</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Croissant+One&family=Kanit:ital,wght@1,300&display=swap" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
</head>
<body style="background-image: url('cul1.jpg.avif'); background-size: cover; background-position: center; margin: 0; font-family: 'Kanit', sans-serif; color: rgb(255, 255, 255);">
    <div class="content-overlay">
        <header>
            <!-- Navigation bar -->
            <!-- Add your navigation bar here -->
        </header>

        <section class="welcome-section">
            <div class="welcome-content">
                <h1>What to know about the Culture of Tajikistan...</h1>
                <p>Explore the rich and vibrant culture of this beautiful country.</p>

                <iframe width="700" height="500" src="https://www.youtube.com/embed/eJjHG70gf_c?si=7lxgVEjIl4C_OakG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
        </section>

        <section class="culture">
            <h1>Different Cultures</h1>

            <div class="row">
                <div class="culture-col">
                    <img src="cull11.jpeg">
                    <h3>National Dressings</h3>
                    <p>Kulob family</p>
                </div>

                <div class="culture-col">
                    <img src="cul111.jpeg">
                    <h3>Pamiri Dress</h3>
                    <p>Pamiri Girl Dance</p>
                </div>

                <div class="culture-col">
                    <img src="culll.jpeg">
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

    .welcome-section h1, .culture h1 {
        font-family: 'Croissant One', cursive;
        font-size: 48px;
        margin-bottom: 20px;
    }

    .welcome-section p {
        font-size: 30px;
    }

    .culture {
        width: 80%;
        margin: auto;
        text-align: center;
        padding-top: 100px;
    }

    .culture h1 {
        color: white; /* Adjusted for visibility */
        font-size: 50px;
    }

    .row {
        display: flex;
        justify-content: space-around;
        flex-wrap: wrap;
    }

    .culture-col {
        flex-basis: 30%; /* Adjust this value as needed */
        margin: 10px;
        border-radius: 10px;
        text-align: center; /* Center align the content */
    }

    .culture-col img {
        width: 100%; /* Adjust image width to fit the container */
        border-radius: 10px;
        margin-bottom: 15px; /* Space between image and text */
    }
</style>

