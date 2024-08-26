<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title> Developer Portfolio</title>
        <link rel = "preconnect" href="https://fonts.googleapis.com">
        <link rel = "preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">

        <style>
            * {
                margin: 3px;
                padding: 0;
            }
        body {
                background-color: rgb(32, 21, 63);
                color: rgb(250, 244, 244);
                font-family: 'Algerian';
            }
        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 72px;
            background-color: rgb(40, 22, 89);
        }
        nav ul {
            display: flex;
            justify-content: center;
        }
        nav ul li {
            list-style: none;
            margin: 0 23px;
        }
        nav ul li a {
            text-decoration: none;
            color: white;
            margin: 0 23px;
        }
        nav ul li a:hover {
                color: rgb(188, 66, 186);
                font-size: 1.04rem;                
        }
        main hr {
            border: 0;
            background: rgb(163, 60, 163);
            height: 1.2px;
            margin: 60px 84px;
        }
        .left {
            font-size: 1.6rem;
        }
        .firstSection{
            display:flex;
            justify-content: space-between;
            align-items: center;
            margin: 130px 110px;
        }
        .first div{
            width: 50%;
        }
        .leftSection{
            font-size: 2.2rem;
        }
        .rightSection img {
                width: 80%;
                height: 720px;
                width: 500px;
        }
        .purple{
            color: rgb(163, 60, 163);
            width:30px;
            margin: 30px;
        }
        .text-gray {
            color: gray;
        }
        #element {
            color: rgb(163, 60, 163) ;
        }
        .secondSection {
            max-width: 80vw;
            margin: auto;
            height: 80px;
        }
        .secondSection h1 {
            font-size: 1.9rem;
        }
        .secondSection .box {
            background: white;
            width: 80vw;
            height: 2px;
            margin: 56px 0;
            display: flex;
        }
        .secondSection .vertical {
            height: 60px;
            width: 1px;
            background-color: white;
            margin: 0 120px;

        }
        .image-top {
            width: 23px;
            position: relative;
            top: -32px;
            left: -9px;
        }
        .vertical-title {
            position: relative;
            top: 29px;
            width: 100px;
            margin: 0 -20px;
        }
        .vertical-desc{
            position: relative;
            top: 35px;
            color:gray;
            width:140px;
            font-size: 1.1rem;
            margin: 0 -35px;
        }
        </style>
    </head>
    <body>
        <header>
        <nav>
            <div class = "left">Rajdeep's Portfolio</div> 
            <div class = "right">
            <ul>
               <li><a href = "/13030823078_Rajdeep Podder.pdf">Home</a></li>
                <li><a href = "/">About Me</a></li>
                <li><a href = "/">Achievemts</a></li>
                <li><a href = "/">My Skills</a></li>
                <li><a href = "/">Contact Me</a></li>
            </ul>
            </div>
        </nav>
        </header>
        <main>
            <section class = "firstSection">
                <div class = "leftSection">
                    Hi, My name is <span class="purple"> Rajdeep</span> 
                    <div>I am a passionate</div>
                    <span id="element"></span>
                </div>
                <div class="rightSection">
                    <img src = "raj.jpg" alt=" ">
                </div>

            </section> 
            <hr>
            <section class="secondSection">
                <span class ="text-gray">
                    Exploring my steps ...
                </span>
                <h1>Work Experience</h1>

                <div class="box"> 
                    <div class="vertical">
                        <image class="image-top" src="dev.png" alt="">
                            <div class="vertical-title">
                                HTML Developer (2010-12)
                            </div>
                     <div class="vertical-desc">
                        Worked in TCS as a HTML intern. 
                        I dealt with 2 mega projects in my internship.
                     </div>
                     <div class="vertical">
                        <image class="image-top" src="dev.png" alt="">
                        <div class="vertical-title">
                            HTML Developer (2010-12)
                        </div>
                 <div class="vertical-desc">
                    Worked in TCS as a HTML intern. 
                    I dealt with 2 mega projects in my internship.
                 </div>
                     <div class="vertical"></div>
                     <div class="vertical"></div>
                </div>
            </section>
            </main>
            <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
             <!-- Setup and start animation! -->
  <script>
    var typed = new Typed('#element', {
      strings: ['Web Desingner','Singer','Coder','Cricketer'],
      typeSpeed: 80,
    });
  </script>
</body>
    </body>  
    </html>
