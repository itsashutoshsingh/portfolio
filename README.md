<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive portfolio </title>
    <link rel="stylesheet" type="text/css" href="style.css">
    <script src="custom.js"></script>


</head>

<body>
    <header>
        <nav>
            <div class="LOGO">PORTFO <span>LIO</span></div>
            <div class="menu">
                <a href="#">Home</a>
                <a href="#">About</a>
                <a href="#">Services</a>




                <a href="#">Contact</a>

                <a href="#">Skills</a>
            </div>
        </nav>
        <div class="text">
            <p>Hello,I am</p>
            <h1> Ashutosh Bhadauriya</h1>
            <p>and i am a front end developer</p>
            <button class="c-btn">Hire me</button>
        </div>




    </header>
    <section id="about">
        <div class="section-info">
            <h1>
                About
            </h1>
            <p> Who AM I</p>
        </div>


        </div>

    </section>
    <div class="container">
        <div class="image">
            <img src="images/about.jpg">
        </div>
        <div class2="text">
            <p>
                this is my portfolio.
                first personal portfolio create .
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis aliquid ipsam explicabo deserunt
                incidunt, vero qui sed corporis cum. Laboriosam, numquam praesentium. Ullam maxime iste facilis, iure
                ratione eum molestiae.

            </p>
            <button class="c-btn">Download cv</button>
        </div>
    </div>
    <section id="Skills">
        <div class="section-info">
            <h1>
                Skills
            </h1>
            <p> What about you</p>
        </div>


        </div>
        <div class="skills-row">
            <div class="skills-left-row">
                <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus hic cupiditate sint velit vitae
                    tenetur, dolores inventore cum aspernatur veniam assumenda quo perferendis, molestiae saepe,
                    architecto pariatur maiores ducimus magni.</p>
                <button class="c-btn">Read more</button>

            </div>
            <div class="skills-right-row">
                <div class="progress-div">
                    <P>
                        <span>HTML</span>
                        <br>
                        <progress value="80" max="100"></progress>
                        <span>80%</span>
                    </P>
                    <P>
                        <span>CSS</span>
                        <br>
                        <progress value="65" max="100"></progress>
                        <span>75%</span>
                    </P>
                    <P>
                        <span>JAVA-SCRIPT</span>
                        <br>
                        <progress value="55" max="100"></progress>
                        <span>88%</span>
                    </P>
                    <P>
                        <span>BOOT-STRAP</span>
                        <br>
                        <progress value="88" max="100"></progress>
                        <span>70%</span>
                    </P>
                    <P>
                        <span>QUERRY</span>
                        <br>
                        <progress value="76" max="100"></progress>
                        <span>75%</span>
                    </P>


                </div>
            </div>
        </div>

    </section>
    <section id="Services">
        <div class="section-info">
            <h1>
                Services
            </h1>
            <p> What We provide</p>
        </div>
        <div class="Services-row">
            <div class="Services-box">
                <img src="images/b2.png">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium deserunt adipisci expedita nemo.
                    Non rerum laboriosam, praesentium vero voluptatum, asperiores deleniti, fugit veritatis optio
                    voluptate mollitia dolores architecto dolorem. Dicta.</p>
            </div>
            <div class="Services-box">
                <img src="images/b2.png">
                <p>Motivational success quotes often feel like our own opinions making a return visit, just augmented by
                    someone with writing talent. And the right quote at the right time can change things—words matter,
                    and motivating phrases can encourage us to get up, overcome tough times, take action, stop
                    procrastinating, escape our comfort zone, motivate a team, invest in personal growth, start a
                    business, and do the hard work that needs</p>
            </div>
            <div class="Services-box">
                <img src="images/b2.png">
                <p>Motivational success quotes often feel like our own opinions making a return visit, just augmented by
                    someone with writing talent. And the right quote at the right time can change things—words matter,
                    and motivating phrases can encourage us to get up, overcome tough times, take action, stop
                    procrastinating, escape our comfort zone, motivate a team, invest in personal growth, start a
                    business, and do the hard work that needs</p>
            </div>
        </div>

    </section>

    </section>
    <section>
        <section id="Contact">
            <div class="Contact-row">
                <div class="Contact-left-col">
                    <img src="images/b3.png">
                </div>
                <div class="Contact-right-col">
                    <form>

                        <input type="text" name="" placeholder="Name">
                        <br>
                        <input type="mail" name="" placeholder="E-mail">
                        <br>
                        <textarea name="" id="" cols="40" rows="10" placeholder="Message"></textarea>
                        <br>
                        <button class="c-btn">Submit</button>


                    </form>
                </div>

            </div>
        </section>
    </section>

</body>

</html>
header {
    width: 100%;
    height: 100vh;
    background: url("../images/b1.png"), url("../images/bg1.jpeg");
    background-size: 50% 100%, cover;
    background-position: right, center;
    background-repeat: no-repeat, no-repeat;
    clip-path: polygon(50% 0%, 100% 0, 100% 75%, 50% 100%, 0% 85%, 0 0);
}

.LOGO {
    color: white;
    font-size: 48px;
    padding-left: 100px;
}

.menu {
    color: white;
    text-decoration: none;
    padding: 10px 20px;
    margin: 5px;
    font-size: 20px;


}

.menu {
    margin-right: 100px;
}

nav {
    width: 100%;
    height: 69px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.LOGO span {
    color: #e74c3c;
}

.menu a:hover {
    background: #e74c3c;
    transition: 0.4;
}

.text {
    color: aliceblue;
    margin-top: 100px;
    margin-left: 100px;
    max-width: 451px;
}

.text h1 {
    font-size: 50px;
    margin: 10px 0px;
}


.text p {
    font-size: 25px;
}

.c-btn {
    border: none;
    outline: none;
    color: azure;
    background-color: #e74c3c;
    padding: 10px;
    margin-top: 20px;

}

#about {
    padding: 100px 50px;
}

.section-info {
    font-weight: bold;
    text-align: center;
}

.section-info h1 {
    font-size: 50px;
}

.section-info p {
    font-size: 25px;
    color: #e74c3c;
}


.container { 
    display: grid;
    align-items: center;
    grid-template-columns: 1fr 1fr 1fr;
    column-gap: 5px;
}

img {
    max-width: 100%;
    max-height: 100%;
}
.text{
    font-size: 70px;
    
}
#Skills{
    padding: 100px 50px;
    background: url("../images/bg2.jpg");
    background-size: cover;
    color: azure;
}
.skills-row{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
}
.skills-left-row{
    flex-basis: 50%;
    text-align: justify;

    
}
.skills-right-row{
    flex-basis: 50%;

}
progress{
    width: 80%;

}
.progress-div{
    width: 70%;
    margin: auto;

}
.progress-div p{
    margin-bottom: 10px;
    font-size: 20px;
    padding-left: 80px;
    text-align: justify;
}
#Services{
    padding: 100px 50px;

}
.Services-row{
    display: flex;
    justify-content: space-around;
    align-items: center;
    flex-wrap: wrap;
}
.Services-box{
    flex-basis: 26%;
    text-align: center;
    box-shadow: 2px 3px 5px green ;
    padding: 20px;
    margin-top: 20px;
}
.Services-box img{
    width: 59%;
}
.Services-box:hover{
    background-color: #e74c3c;
    color: white;
    transition: 0.5s;
}
#Contact{
    padding: 100px 50;
    background: linear-gradient(150deg, #e74c3c 45%, white 0%);
}
.Contact-row{
    display: flex;
    justify-content: ce;
    align-items: center;
    flex-wrap: wrap;
}
.Contact-left-col{
    flex-basis: 50%;
}
.Contact-right-col{
    flex-basis: 50%;}
    .Contact-right-col form{
        text-align: center;
    }
    .Contact-right-col form input{
        width: 59%;
        padding: 10px;
        margin-bottom: 10px;

    }
    .Contact-right-col form  textarea{
        width: 59;
        padding: 10px;
    }
