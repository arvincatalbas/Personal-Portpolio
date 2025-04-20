<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arvin Personal Portfolio</title>
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header class="header">
        <a href="#" class="logo">Portfolio</a>

        <i class='bx bx-menu' id="menu-icon"></i>

        <nav class="navbar">
            <a href="#home" class="active">home</a>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#portfolio">Portfolio</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="home" id="home">
        <div class="home-content">
            <h3>Hello, It's Me</h3>
            <h1>Arvin</h1>
            <h3>And I'm a <span class="multiple-text"></span></h3>
            <p>A Third Year Students of Bachelor of Science in Information Technology at Sorsogon State University - Bulan Campus</p>
            <div class="social-media">
                <a href="#"><i class='bx bxl-facebook'></i></a>
                <a href="#"><i class='bx bxl-twitter'></i></a>
                <a href="#"><i class='bx bxl-instagram-alt'></i></a>
                <a href="#"><i class='bx bxl-tiktok'></i></a>
            </div>
            <a href="#" class="btn">Download CV</a>
        </div>

        <div class="home-img">
            <img src="man-with-tablet-min.png" alt="">
        </div>
    </section>

    <section class="about" id="about">
        <div class="about-img">
            <img src="men.png" alt="">
        </div>

        <div class="about-content">
            <h2 class="heading">About <span>Me</span></h2>
            <h3>Web Developer</h3>
            <p>Hi! I'm a passionate web developer with a knack for creating beautiful and functional websites. I love coding, solving
            problems, and bringing ideas to life.</p>
            <a href="#" class="btn">Read More</a>
        </div>
    </section>

    <section class="services" id="services">
        <h2 class="heading">Our <span>Services</span></h2>

        <div class="services-container">
            <div class="services-box">
                <i class='bx bx-code-alt'></i>
                <h3>Web Development</h3>
                <p>Build responsive and user-friendly websites using HTML, CSS, and JavaScript.</p>
                <a href="#" class="btn">Read More</a>
            </div>

            <div class="services-box">
                <i class='bx bxs-paint'></i>
                <h3>Graphic Design</h3>
                <p>Build responsive and user-friendly websites using HTML, CSS, and JavaScript.</p>
                <a href="#" class="btn">Read More</a>
            </div>

            <div class="services-box">
                <i class='bx bx-bar-chart-alt'></i>
                <h3>Digital Marketing</h3>
                <p>Build responsive and user-friendly websites using HTML, CSS, and JavaScript.</p>
                <a href="#" class="btn">Read More</a>
            </div>
        </div>
    </section>

    <section class="portfolio" id="portfolio">
        <h2 class="heading">Latest <span>Project</span></h2>

        <div class="portfolio-container">
            <div class="portfolio-box">
                <img src="p1.jpg" alt="">
                <div class="portfolio-layer">
                    <h4>Web Design</h4>
                    <p>This is my project, a web design project.</p>
                    <a href="#"><i class='bx bx-link-external'></i></a>
                </div>
            </div>

            <div class="portfolio-box">
                <img src="image2(3).jpg" alt="">
                <div class="portfolio-layer">
                    <h4>Web Design</h4>
                    <p>This is my project, a web design project.</p>
                    <a href="#"><i class='bx bx-link-external'></i></a>
                </div>
            </div>

            <div class="portfolio-box">
                <img src="image3(4).jpg" alt="">
                <div class="portfolio-layer">
                    <h4>Web Design</h4>
                    <p>This is my project, a web design project.</p>
                    <a href="#"><i class='bx bx-link-external'></i></a>
                </div>
            </div>
    </section>

    <section class="contact" id="contact">
        <h2 class="heading">Contact <span>Me!</span></h2>

        <form action="#">
            <div class="input-box">
                <input type="text" placeholder="Full Name">
                <input type="email" placeholder="Email Address">
            </div>
            <div class="input-box">
                <input type="Number" placeholder="Mobile Number">
                <input type="text" placeholder="Email Subject">
            </div>
            <textarea name="" id="" cols="30" rows="10" placeholder="Your Message"></textarea>
            <input type="submit" value="Send Message" class="btn">
        </form>
    </section>

    <footer class="footer">
        <div class="footer-text">
            <p>Copyright &copy; 2024 | All Rights Reserved.</p>
        </div>

        <div class="footer-iconTop">
            <a href="#home"><i class='bx bx-up-arrow-alt'></i></a>
        </div>
    </footer>

    <script src="https://unpkg.com/scrollreveal"></script>

    <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>

    <script src="script.js"></script>
</body>
</html>
