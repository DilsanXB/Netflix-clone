# Netflix-clone
Netflix clone with html and css

HTML

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix Nepal - Watch TV Shows Online, Watch Movies Online</title>
    <link rel="shortcut icon" href="assets/images/favicon.ico" type="image/x-icon">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="media-quarie.css">
</head>

<body>
    <!-- MAIN START  -->

    <div class="main">
        <nav>
            <span><img width="53" src="assets/images/logo.svg" alt=""></span>
            <div>
                <button class="btn"> <span class="lan-ico"><i class="fa-solid fa-language"></span></i>English <span> <i
                            class="fa-solid fa-angle-down"></i></span> </button>
                <button class="btn btn-red-sm">Sign In</button>
            </div>
        </nav>
        <div class="box">
        </div>
        <div class="hero">
            <span>Enjoy big movies, hit series and more from ₹ 149.</span>
            <span>Join today. Cancel anytime.</span>
            <span>Ready to watch? Enter your email to create or restart your membership.</span>
            <div class="hero-buttons">
                <input type="text" placeholder="Email Address">
                <button class="btn btn-red">Get Started &gt;</button>
            </div>
        </div>
        <div class="seperation"></div>

        <!-- MAIN END -->



        <section class="first-sec">
            <div class="about">
                <span>Enjoy on your TV</span>
                <span>Watch on smart TVs, PlayStation, Xbox, Chromecast, Apple TV, Blu-ray players and more.</span>
            </div>

            <div class="sec-image">
                <img src="assets/images/tv.png" alt="">
                <video width="425px"
                    src="https://media.istockphoto.com/id/2181284175/video/a-warm-and-festive-chalet-in-a-winter-forest-featuring-a-sparkling-christmas-tree-a-cozy-fire.mp4?s=mp4-640x640-is&k=20&c=08spoy1Ye9VcKunjXV7_yuksoT-me5bOki-QiGMfnbU="
                    autoplay loop muted></video>
            </div>
        </section>
        <div class="seperation"></div>
        <!-- FIRST SECTION END -->



        <section class="first-sec second-sec">

            <div class="sec-image">
                <img src="assets/images/netflix-phone.png" alt="Phone">
            </div>
            <div class="about">
                <span>Downnload your shows to watch offline</span>
                <span>Save your favourites easily and always have something to watch.</span>
            </div>
        </section>
        <div class="seperation"></div>
        <!-- SECOND SECTION  END-->



        <section class=" first-sec thrid-sec">
            <div class="about">
                <span>Watch everywhere</span>
                <span>Stream unlimited movies and Tv shows on your phone, tablet, laptop, and Tv.</span>
            </div>

            <div class=" sec-image sec-img-third ">
                <img src="assets/images/tv.png" alt="">
                <video width="425px" src="assets/videos/video1.mp4" autoplay loop muted></video>

            </div>
        </section>
        <div class="seperation"></div>

        <!-- THIRD SECTION END  -->


        <section class=" first-sec thrid-sec">
            <div class=" sec-image sec-img-third ">
                <img src="assets/images/children.jpg" alt="">

            </div>
            <div class="about">
                <span>Create profiles for kids</span>
                <span>send children on adventures with their favourite characters in
                    a space made just for them-free with your membership.
                </span>
            </div>
        </section>
        <div class="seperation"></div>

        <!-- FORTH SECTION END -->


        <!-- SUBFOOTER SECTION START-->
        <section class="faq">
            <h2>Frequently Asked Questions</h2>
            <div class="faq-box">
                <span>What is Netflix? </span><span class="plus-sign"> <i class="fa-solid fa-plus"></i></span>
            </div>
            <div class="faq-box">
                <span>How much does Netflix cost? </span><span class="plus-sign"> <i
                        class="fa-solid fa-plus"></i></span>
            </div>
            <div class="faq-box">
                <span>Where can I watch? </span><span class="plus-sign"> <i class="fa-solid fa-plus"></i></span>
            </div>
            <div class="faq-box">
                <span>How do I cancel? </span><span class="plus-sign"> <i class="fa-solid fa-plus"></i></span>
            </div>
            <div class="faq-box">
                <span>What can I watch on Netflix? </span><span class="plus-sign"> <i
                        class="fa-solid fa-plus"></i></span>
            </div>
            <div class="faq-box">
                <span>Is Netflix good for kids? </span><span class="plus-sign"> <i class="fa-solid fa-plus"></i></span>
            </div>
        </section>
        <div class="seperation"></div>

        <footer>
            <div class="questions">
                Questions? Call <span style="text-decoration: underline;"> 000-800-919-1694</span></div>
            <div class="footer">
                <div class="footer-items">

                    <a href="faq">FAQ</a>
                    <a href="faq">Investor Relations</a>
                    <a href="faq">Privacy</a>
                    <a href="faq">Speed Test</a>
                    <!-- <button class=" btn-lang" ><span class="lan-ico"><i class="fa-solid fa-language"></span>English <i class="fa-solid fa-angle-down"></i></button> -->
                    <a href="faq" style="text-decoration: none;">Netflix India</a>
                </div>
                <div class="footer-items">
                    <a href="faq">Help Centre</a>
                    <a href="faq">Job</a>
                    <a href="faq">Cookie Preferences</a>
                    <a href="faq">Legal Notices</a>

                </div>
                <div class="footer-items">
                    <a href="faq">Account</a>
                    <a href="faq">Corporate Information</a>
                    <a href="faq">Ways to Watch</a>
                    <a href="faq">Only on Netflix</a>

                </div>
                <div class="footer-items">
                    <a href="faq">Media Centre</a>
                    <a href="faq">Terms of Use</a>
                    <a href="faq">Contact Us</a>

                </div>
            </div>

        </footer>




        <script src="https://kit.fontawesome.com/28197f36da.js" crossorigin="anonymous"></script>

</html>


CSS 

@import url('https://fonts.googleapis.com/css2?family=Martel+Sans:wght@200;300;400;600;700;800;900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

* {
    padding: 0;
    margin: 0;
    font-family: "Poppins", sans-serif;
}

body {
    background-color: black;
}


.main {
    background-image: url(assets/images/bg.jpg);
    background-position: center center;
    background-repeat: no-repeat;
    background-size: max(1200px, 100vw);
    height: 644px;
    position: relative;
}

.main .box {
   height: 644px;
    width: 100%;
    opacity: 0.69;
    background-color: black;
    position: absolute;
    top: 0;

}
   

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 60vw;
    margin: auto;
    height: 100px;
    
    
}
  

nav img {
    width: 130px;
    color: red;
    position: relative;
    z-index: 10;

    
}

nav button {
    position: relative;
    z-index: 10;
}

.hero {
    height: calc(100% - 100px);
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    color: white;
    position: relative;
    font-family: "Martel Sans", sans-serif;
    gap: 23px;
    padding: 0 30px;

}

.hero> :nth-child(1) {
    font-family: "Poppins", sans-serif;

    font-weight: 600;
    font-size: 38px;
    text-align: center;
}

.hero> :nth-child(2) {
    font-size: 20px;
    font-weight: 400;
    text-align: center;

}

.hero> :nth-child(3) {
    font-size: 17px;
    font-weight: 400;
    text-align: center;

}



.btn {
    padding: 3px 8px;
    font-weight: 400;
    color: white;
    background-color: rgba(248, 243, 243, 0.025);
    border: 1px solid white;
    border-radius: 4px;
    cursor: pointer;
}
.btn .lan-ico {
    margin-right: 8px;
}

.hero-btn {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 12px;
}

.btn-red {
    background-color: red;
    color: white;
    border: none;
    padding: 6px 24px;
    font-size: 18px;
    border-radius: 4px;
    font-weight: 400;
    font-family: "Poppins", sans-serif;
    margin-left: 6px;
}

.btn-red-sm {
    background-color: red;
    color: white;
    border: none;
    margin-left: 10px;
}

.main input {
    padding: 7px 101px 7px 14px;
    font-size: 12px;
    border-radius: 4px;
    font-weight: 500;
    border: 0.3px solid rgba(255, 255, 255, 0.7);
    background-color: rgba(23, 23, 23, 0.5);
    /* font-weight: 500; */
    color: white;
}

.seperation {
    height: 7px;
    background-color: rgb(49, 48, 48);
}

.first-sec {
    display: flex;
    justify-content: center;
    max-width: 70vw;
    margin: auto;
    color: white;
    align-items: center;
    padding: 20px 0;
}

.sec-image {
    position: relative;
}

.first-sec .sec-image img {
    width: 460px;
    position: relative;
    z-index: 10;
}

.sec-image video {
    width: 425px;
    position: absolute;
    top: 5px;
    left: 5px;
}


.about {
    display: flex;
    flex-direction: column;
    padding: 34px 0;
}

.first-sec div :nth-child(1) {
    font-size: 40px;
    font-weight: bold;
}

.first-sec div :nth-child(2) {
    font-size: 16px;
}

.second-sec .sec-image img {
    width: 520px;
}
.faq {
    background: black;
    color: white;
    padding: 34px;
    font-size: 19px;
}
.faq h2 {
    text-align: center;
    margin-bottom: 32px;
    color: rgb(255, 255, 255);

}

.faq .faq-box {
    background-color: rgb(44, 42, 42);
    padding: 25px;
    max-width: 50vw;
    margin: 10px auto;
    display: flex;
    justify-content: space-between;
    cursor: pointer;
    transition: all 0.5s;
    border-radius: 3px;
    

}
.faq .faq-box:hover {
    background-color: rgb(60, 60, 60);


}
.plus-sign {
    color: rgb(255, 255, 255);

}
.plus-sign:hover {
    color: #000000;
}
footer {
    color: rgb(202, 199, 199);
    max-width: 60vw;
    margin: auto;
    padding: 14px;
}

.footer {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    color: rgb(229, 224, 224);
    
}
.footer-items {
    display: flex;
    flex-direction: column;
    row-gap: 5px;

}
.footer .footer-items a {
    
    font-size: 14px;
    color: rgb(168, 165, 165);
    gap: 23px;

}
footer .questions {
    padding: 34px 0;
}

MEDIA QUERIES

@media screen and (max-width: 1300px) {
    .first-sec {
        flex-wrap: wrap;
    }

    .first-sec div :nth-child(1) {
        font-size: 30px;
        font-weight: bold;
    }

    .first-sec div :nth-child(2) {
        font-size: 14px;
    }

    .second-sec .sec-image img {
        width: 520px;
    }

    .footer {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        color: rgb(229, 224, 224);

    }
}

@media screen and (max-width: 1000px) {
    .hero {
        height: calc(100% - 100px);
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        color: white;
        position: relative;
        font-family: "Martel Sans", sans-serif;
        gap: 16px;
        padding: 0 30px;

    }

    .hero> :nth-child(1) {
        font-family: "Poppins", sans-serif;

        font-weight: 600;
        font-size: 25px;
        text-align: center;
    }

    .hero> :nth-child(2) {
        font-size: 18px;
        font-weight: 400;
        text-align: center;

    }

    .hero> :nth-child(3) {
        font-size: 10px;
        font-weight: 400;
        text-align: center;

    }

    .hero-btn {
        display: flex;

        align-items: center;
        justify-content: center;
        gap: 12px;
    }

    .btn-red {
        background-color: red;
        color: white;
        border: none;
        padding: 4px 8px;
        font-size: 13px;

        border-radius: 4px;
        font-family: "Poppins", sans-serif;
        margin-left: 6px;
    }

    .main input {
        padding: 4px 40px 4px 8px;
        font-size: 13px;
        border-radius: 4px;
        font-weight: 500;
        border: 0.3px solid rgba(255, 255, 255, 0.7);
        background-color: rgba(23, 23, 23, 0.5);
        /* font-weight: 500; */
        color: white;
    }

    nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
        max-width: 75vw;
        margin: auto;
        height: 100px;


    }

    nav img {
        width: 100px;
        color: red;
        position: relative;
        z-index: 10;


    }

    .main {
        background-image: url(assets/images/bg.jpg);
        background-position: center center;
        background-repeat: no-repeat;
        background-size: max(1200px, 100vw);
        height: 444px;
        position: relative;
    }

    .main .box {
        height: 444px;
        width: 100%;
        opacity: 0.69;
        background-color: black;
        position: absolute;
        top: 0;

    }

}

@media screen and (max-width: 800px) {
    .hero> :nth-child(1) {
        font-family: "Poppins", sans-serif;

        font-weight: 500;
        font-size: 18px;
        text-align: center;
    }

    .hero> :nth-child(2) {
        font-size: 13px;
        font-weight: 400;
        text-align: center;

    }

    .hero> :nth-child(3) {
        font-size: 10px;
        text-align: center;

    }

    .hero {
        height: calc(100% - 80px);
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        color: white;
        position: relative;
        font-family: "Martel Sans", sans-serif;
        gap: 10px;
        padding: 0 30px;

    }

    .main {
        background-image: url(assets/images/bg.jpg);
        background-position: center center;
        background-repeat: no-repeat;
        background-size: max(1200px, 100vw);
        height: 350px;
        position: relative;
    }

    nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
        max-width: 70vw;
        margin: auto;
        height: 80px;


    }

    .main .box {
        height: 350px;
        width: 100%;
        opacity: 0.69;
        background-color: black;
        position: absolute;
        top: 0;

    }

    .first-sec {
        display: flex;
        justify-content: center;
        max-width: 70vw;
        margin: auto;
        color: white;
        align-items: center;
        padding: 10px 0;
    }

    .first-sec {
        flex-wrap: wrap;
    }

    .first-sec div :nth-child(1) {
        font-size: 22px;
        font-weight: bold;
        margin-bottom: 5px;
    }

    .first-sec div :nth-child(2) {
        font-size: 12px;
    }

    .first-sec .sec-image img {
        width: 360px;
        position: relative;
        z-index: 10;
    }

    .sec-image video {
        width: 325px;
        position: absolute;
        top: 5px;
        left: 5px;
    }

    .faq {
        background: black;
        color: white;
        padding: 34px;

    }

    .faq h2 {
        text-align: center;
        margin-bottom: 12px;
        color: rgb(99, 94, 243);
        font-size: 20px;

    }

    .faq .faq-box {
        background-color: rgb(44, 42, 42);
        padding: 16px;
        max-width: 45vw;
        margin: 20px auto;
        display: flex;
        justify-content: space-between;
        cursor: pointer;
        border-radius: 3px;

    }

    footer {
        color: rgb(202, 199, 199);
        max-width: 70vw;
        margin: auto;
        padding: 14px;
    }

    .footer {
        display: grid;
        grid-template-columns: 1fr 1fr;
        color: rgb(229, 224, 224);

    }

    .footer .footer-items a {

        font-size: 13px;
        color: rgb(168, 165, 165);
        gap: 40px;

    }
}

@media screen and (max-width: 600px) {
    .hero {
        height: calc(100% - 80px);
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        color: white;
        position: relative;
        font-family: "Martel Sans", sans-serif;
        gap: 10px;
        padding: 0 30px;

    }

    .hero> :nth-child(1) {
        font-family: "Poppins", sans-serif;

        font-weight: 500;
        font-size: 20px;
        text-align: center;
    }

    .hero> :nth-child(2) {
        font-size: 14px;
        font-weight: 400;
        text-align: center;

    }

    .hero> :nth-child(3) {
        font-size: 10px;
        text-align: center;

    }

    .hero-btn {
        display: grid;
        align-items: center;
        justify-content: center;
        gap: 12px;
    }



    .main input {
        padding: 4px 20px 4px 8px;
        font-size: 10px;
        border-radius: 4px;
        font-weight: 500;
        border: 0.3px solid rgba(255, 255, 255, 0.7);
        background-color: rgba(23, 23, 23, 0.5);
        /* font-weight: 500; */
        color: white;
    }

    .main {
        background-image: url(assets/images/bg.jpg);
        background-position: center center;
        background-repeat: no-repeat;
        background-size: max(1200px, 100vw);
        height: 340px;
        position: relative;

    }

    .main .box {
        height: 340px;
        width: 100%;
        opacity: 0.69;
        background-color: black;
        position: absolute;
        top: 0;
    }

    .btn {
        padding: 2px 5px;
        color: white;
        background-color: rgba(248, 243, 243, 0.025);
        border: 1px solid white;
        border-radius: 4px;
        cursor: pointer;
        font-size: 10px;

    }

    .btn-red-sm {
        background-color: red;
        color: white;
        border: none;
        margin-left: 15px;
    }

    .btn-red {
        background-color: rgb(255, 0, 0);
        color: white;
        border: none;
        padding: 4px 8px;
        font-size: 10px;

        border-radius: 4px;
        font-family: "Poppins", sans-serif;
        margin-left: 6px;
        margin-top: 20px;
    }

    nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
        max-width: 80vw;
        margin: auto;
        height: 80px;


    }

    nav img {
        width: 90px;
        color: red;
        position: relative;
        z-index: 10;

    }


}

@media screen and (max-width:400px) {
    .first-sec {
        display: flex;
        justify-content: center;
        max-width: 90vw;
        margin: auto;
        color: white;
        align-items: center;
        padding: 10px 0;
    }

    .first-sec .sec-image img {
        width: 260px;
        position: relative;
        z-index: 10;
    }

    .sec-image video {
        width: 235px;
        position: absolute;
        top: 5px;
        left: 5px;
    }

    .faq {
        background: black;
        color: white;
        padding: 20px;


    }

    .faq h2 {
        text-align: center;
        margin-bottom: 25px;
        color: rgb(255, 255, 255);

    }

    .faq .faq-box {
        background-color: rgb(44, 42, 42);
        padding: 15px;
        max-width: 50vw;
        margin: 10px auto;
        display: flex;
        justify-content: space-between;
        cursor: pointer;
        transition: all 0.5s;
        border-radius: 3px;
        font-size: 12px;
    }

    .first-sec div :nth-child(1) {
        font-size: 20px;
        font-weight: bold;
        text-align: center;
    }

    .first-sec div :nth-child(2) {
        font-size: 12px;
        text-align: center;
    }


}

@media screen and (max-width: 320px) {
    .main {
        background-image: url(assets/images/bg.jpg);
        background-position: center center;
        background-repeat: no-repeat;
        background-size: max(1200px, 100vw);
        height: 344px;
        position: relative;
    }

    .main .box {
        height: 344px;
        width: 100%;
        opacity: 0.5;
        background-color: black;
        position: absolute;
        top: 0;

    }

    nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
        max-width: 80vw;
        margin: auto;
        height: 50px;


    }


    nav img {
        width: 70px;
        color: red;
        position: relative;
        z-index: 10;


    }

    .hero> :nth-child(1) {
        font-family: "Poppins", sans-serif;

        font-weight: 600;
        font-size: 16px;
        text-align: center;
    }

    .hero> :nth-child(2) {
        font-size: 14px;
        font-weight: 400;
        text-align: center;

    }

    .hero> :nth-child(3) {
        font-size: 8px;
        font-weight: 400;
        text-align: center;

    }

    .btn {
        padding: 1px 3px;
        color: white;
        background-color: rgba(248, 243, 243, 0.025);
        border: 1px solid white;
        border-radius: 4px;
        cursor: pointer;
    }

    .btn-red {
        background-color: red;
        color: white;
        border: none;
        padding: 2px 4px;
        border-radius: 4px;
        font-weight: 400;
        font-family: "Poppins", sans-serif;
        margin-left: 6px;
    }

    .btn-red-sm {
        background-color: red;
        color: white;
        border: none;
        margin-left: 10px;
    }

    .main input {
        padding: 2px 30px 2px 4px;
        border-radius: 4px;
        border: 0.3px solid rgba(255, 255, 255, 0.7);
        background-color: rgba(23, 23, 23, 0.5);
        color: white;
    }

    .hero {
        height: calc(100% - 50px);
    }

    footer {
        color: rgb(202, 199, 199);
        max-width: 70vw;
        margin: auto;
        padding: 14px;
    }


    .footer {
        display: grid;
        grid-template-columns: 1fr 1fr;
        color: rgb(229, 224, 224);

    }

    .footer .footer-items a {

        font-size: 8px;
        color: rgb(168, 165, 165);
        gap: 40px;

    }

    footer .questions {
        padding: 10px 0px;

    }

    footer .questions h2 {
        font-size: 12px;

    }

    .faq {
        background: black;
        color: white;
        padding: 34px;
        font-size: 19px;
    }

    .faq h2 {
        text-align: center;
        margin-bottom: 32px;
        color: rgb(255, 255, 255);

    }

    .faq .faq-box {
        background-color: rgb(44, 42, 42);
        padding: 25px;
        max-width: 50vw;
        margin: 10px auto;
        display: flex;
        justify-content: space-between;
        cursor: pointer;
        transition: all 0.5s;
        border-radius: 3px;


    }

    .about {
        display: flex;
        flex-direction: column;
        padding: 12px 0;
    }

    .first-sec div :nth-child(1) {
        font-size: 16px;
        text-align: center;
    }

    .first-sec div :nth-child(2) {
        font-size: 9px;
        text-align: center;
    }

    .first-sec .sec-image img {
        width: 220px;
        position: relative;
        z-index: 10;
    }

    .sec-image video {
        width: 200px;
        position: absolute;
        top: 5px;
        left: 5px;
    }


}
