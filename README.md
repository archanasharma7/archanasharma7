<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Portfolio Website</title>
    <!-- Link To CSS -->
    <link rel="stylesheet" href="./css/style.css">
    <!-- Box Icons -->
    <link rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/boxicons@latest/css/boxicons.min.css">
 
</head>
<body>
    <!-- Navbar -->
    <header>
        <a href="#" class="logo">Coding Home</a>
 
        <div class="bx bx-menu" id="menu-icon"></div>
 
        <ul class="navbar">
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#contact">Contact</a></li>
            <div class="bx bx-moon" id="darkmode"></div>
        </ul>

        
    </header>
    <!-- Home -->
 
    <section class="home" id="home">
        <div class="social">
            <a href="#"><i class='bx bxl-github'></i></a>
            <a href="#"><i class='bx bxl-dribbble' ></i></a>
            <a href="#"><i class='bx bxl-behance' ></i></a>
        </div>
        <div class="home-img">
            <img src="Tony-Stark.webp" alt="">
        </div>
        <div class="home-text">
            <span>Hello, I'm</span>
            <h1>Shantanu </h1>
            <h2>Frontend Developer</h2>
            <p>Lorem ipsum dolor sit amet cons <br> adipisicing elit. Minima, consectetur <br> ullam?</p>
            <a href="#contact" class="btn">Contact Me</a>
        </div>
 
    </section>
    <!-- About -->
    <section class="about" id="about">
        <div class="heading">
            <h2>About Me</h2>
            <span>Introduction</span>
        </div>
        <!-- About Content -->
        <div class="about-container">
            <div class="about-img">
                <img src="121.jpg" alt="">
            </div>
            <div class="about-text">
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Omnis beatae eius quae ab consequatur est perferendis dicta. Ad repellendus perferendis minus sunt error eos dicta enim accusantium ipsum veniam debitis quasi sint cum fugiat porro quam, blanditiis a ratione quod!</p>
                <div class="information">
                    <!-- Box 1 -->
                    <div class="info-box">
                        <i class='bx bxs-user' ></i>
                        <span>Tasnia Farin</span>
                    </div>
                    <!-- Box 2 -->
                    <div class="info-box">
                        <i class='bx bxs-phone' ></i>
                        <span>+1 444 444 4444</span>
                    </div>
                    <!-- Box 3 -->
                    <div class="info-box">
                        <i class='bx bxs-envelope' ></i>
                        <span>project@farin.com</span>
                    </div>
                </div>
                <a href="#" class="btn">Download Cv</a>
            </div>
        </div>
    </section>
    <!-- Skills -->
    <section class="skills" id="skills">
        <div class="heading">
            <h2>Skills</h2>
            <span>My Skills</span>
        </div>
        <!-- Skills Content -->
        <div class="skills-container">
            <div class="bars">
                <!-- Box 1 -->
                <div class="bars-box">
                    <h3>HTML</h3>
                    <span>94%</span>
                    <div class="light-bar"></div>
                    <div class="percent-bar html-bar"></div>
                </div>
                <!-- Box 2 -->
                <div class="bars-box">
                    <h3>CSS</h3>
                    <span>84%</span>
                    <div class="light-bar"></div>
                    <div class="percent-bar css-bar"></div>
                </div>
                <!-- Box 3 -->
                <div class="bars-box">
                    <h3>JavaScript</h3>
                    <span>74%</span>
                    <div class="light-bar"></div>
                    <div class="percent-bar js-bar"></div>
                </div>
                <!-- Box 4 -->
                <div class="bars-box">
                    <h3>React</h3>
                    <span>80%</span>
                    <div class="light-bar"></div>
                    <div class="percent-bar react-bar"></div>
                </div>
            </div>
            <div class="skills-img">
                <img src="123.png" alt="">
            </div>
        </div>
 
    </section>
    <!-- Services -->
    <section class="services" id="services">
        <div class="heading">
            <h2>Services</h2>
            <span>Our Services</span>
        </div>
        <div class="services-content">
            <!-- Box 1 -->
            <div class="services-box">
                <i class='bx bx-code-alt' ></i>
                <h3>Web Development</h3>
                <a href="#">Learn More</a>
            </div>
            <!-- Box 2 -->
            <div class="services-box">
                <i class='bx bx-server' ></i>
                <h3>Backend Development</h3>
                <a href="#">Learn More</a>
            </div>
            <!-- Box 3 -->
            <div class="services-box">
                <i class='bx bx-brush' ></i>
                <h3>UI/UX Design</h3>
                <a href="#">Learn More</a>
            </div>

            <div class="services-box">
                <i class='bx bxl-wordpress' ></i>
                <h3>Wordpress Developer</h3>
                <a href="#">Learn More</a>
            </div>
        </div>
    </section>
    <!-- Portfolio -->
    <section class="portfolio" id="portfolio">
        <div class="heading">
            <h2>Portfolio</h2>
            <span>Our Recent Work</span>
        </div>
        <div class="portfolio-content">
            <div class="portfolio-img">
                <img src="blog-2.jpg" alt="">
            </div>
            <div class="portfolio-img">
                <img src="blog-3.jpg" alt="">
            </div>
            <div class="portfolio-img">
                <img src="blog-4.jpg" alt="">
            </div>
            <div class="portfolio-img">
                <img src="blog-5.jpg" alt="">
            </div>
            <div class="portfolio-img">
                <img src="blog-6.jpg" alt="">
            </div>
            <div class="portfolio-img">
                <img src="blog-7.jpg" alt="">
            </div>
            
        </div>
    </section>
    <!-- Contact -->
    <section class="contact" id="contact">
        <div class="heading">
            <h2>Contact</h2>
            <span>Connect With Us</span>
        </div>
        <div class="contact-form">
            <form action="">
                <input type="text" placeholder="Your Name">
                <input type="email" name="" id="" placeholder="Your Email">
                <textarea name="" id="" cols="30" rows="10" placeholder="Write Message Here..."></textarea>
                <input type="button" value="Send" class="contact-button">
            </form>
        </div>
    </section>
    <!-- Footer -->
    <div class="footer">
        <h2>Coding Home</h2>
        <div class="footer-social">
            <a href="#"><i class='bx bxl-facebook' ></i></a>
            <a href="#"><i class='bx bxl-twitter' ></i></a>
            <a href="#"><i class='bx bxl-instagram' ></i></a>
            <a href="#"><i class='bx bxl-youtube' ></i></a>
        </div>
 <script src="js/script.js"></script>
    </body>
    </html>
