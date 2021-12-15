# portfolio
my portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My awesome portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700&family=Poppins:wght@400;600&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <div class="site-main-wrapper">
        <button class="hamberger">
            <img src="./images/hamberger.svg" alt="">
        </button>
        <div class="mobile-nav">
            <button class="times"><img src="./images/times.svg" alt=""></button>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Education</a></li>
                <li><a href="#">Skills</a></li>
                <li><a href="#">Contact</a></li>

            </ul>
        </div>
        <header>
            <div class="container">
                <nav id="main-nav" class="flex items-centre justify-between">
                    <div class="left flex items-centre ">
                        <div class="branding">
                            <img src="./images/logo.svg" alt="">
                        </div>
                        <div>
                            <a href="#">Home</a>
                            <a href="#about">About</a>
                            <a href="#education">Education</a>
                            <a href="#skills">Skills</a>
                            <a href="#contact">Contact</a>
                        </div>
                    </div>
                    <div classs="right">
                        <button class="btn btn-primary">Contact</button>
                    </div>  
                </nav>
                <div class="hero flex items-centre justify-between">
                    <div class="left flex-1 flex justify-centre">
                        <img src="./images/man.png" alt="">
                    </div>
                    <div class="right flex-1">
                        <h6>Vijay Vardhan</h6>
                        <h1>This is my  <span>Portfolio</span>
                        </h1>
                        <h2>I'm a Creative Designer </h2>
                        <div>
                            <button class="btn btn-secondary">Download CV</button>
                        </div>
                        
                    </div>
                </div>
            
            </div>
        </header>
    
        <section id="about" class="about">
            <div class="container flex items-centre about-innear-wrap">
                <div class="flex-1">
                    <img class="about-me-img" src="./images/man-2.png" alt="">
                </div>
                <div class="flex-1 right">
                    <h1>About <span>Me</span></h1>
                    <h3>Hello, I'm vardhan</h3>
                    <p> I am very much intrested in coding and I'm a quick learner.
                        I will complete my work on time and perfectly. I am intretsed in learning new things which I don't know
                        I enjoy taking complex problems and turning them into simple and beautiful interface designs.
                        I also love the logic and structure of coding.   
                    </p>
                    
                </div>
            </div>
        </section>
        <section id="education" class="Education">
            <h1>Education</h1>
            <p1><span>Present:</span>&nbsp&nbsp&nbsp&nbspFirst year integrated Mtech student at vit ap</p1>
            <br>
            <br>
            <p2><span>Inter-Mediate:</span>&nbsp&nbsp&nbsp&nbspNarayana J.R collage guntur</p2>
            <br>
            <br>
            <p3><span>School:</span>&nbsp&nbsp&nbsp&nbsp Kendriya Vidyalaya NO.1 Uppal Hyderabad</p3>  
        </section>
        <section id="skills" class="Skills">
            <h1>My <span>Skills</span></h1>
            <div class="container flex">
                <nav class="flex items-centre justify-between">
                    <div class="left">
                        <h3>Web Development:</h3>
                        <p>Web Development is all about building Webpages. It invovles in building, creating, and maintaining of websites. I am very much interested in web development and especially Front-end web development. So I am improving my skills in this aspect.</p>
                        <h3>Communication Skills:</h3>
                        <p>Good communication skills are essential to allow others and yourself to understand information more accurately and quickly. This quality is very much needed to lead a team and this skill helps in maintaining good relationship with people around us. So I am improving in this aspect.</p>
                        <h3>Leadership skills:</h3>
                        <p>Leadership is a vital management function which helps in achievement of team goals. A person with good leadership skills maintain high ethical and moral values. So I am improving my self in this aspect.</p>
                        <h3>Management skills:</h3>
                        <p>Management skills helps in achieving group goals. It helps in building good relationships with people at all levels. It helps in business planning, decision making, problem solving and lot more. So I am improving in this aspect.</p>
                    </div>
                </nav>
            </div>
        </section>
        <section id="contact" class="Contact">
            <h1>My <span>Contact</span> Details</h1>
            <br>
            <br>
            <p1><span>Phone no:</span> 6302004028</p1>
            <br>
            <p2><span>Email-I'D</span>praneeth1062003@gmail.com</p2>
            <br>
            <p3><span>Instagram:</span>__vijay__vardhan__</p3>
        </section>
    </div>
    <script src="./js/app.js"></script>
</body>
</html>
