# SelfPortfolio
Adding my owm portfolio as a web development project

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="portfolio.css">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <script src="#"></script>
</head>
<body>
    <header class="header">
        <a href="#" class="logo">Portfolio.</a>

        <nav class="navbar">
            <a href="#" style="--i:1" class="active">Home</a>
            <a href="#about" style="--i:2">About</a>
            <a href="#Skills" style="--i:3">Skill</a>
            <a href="#project" style="--i:4">Portfolio</a>
            <a href="#contact" style="--i:5">Contact</a>
        </nav>
    </header>
    
    <section class="home">
        <div class="home-content">
            <h3>Hello ,It's Me</h3>
            <h1>Shreya Sachan</h1>
            <h3>And I'm a <span class="text"></span></h3>
            <p>I'm a Web Designer with extensive experience for over 2 years.<br>
            Experienced to create and Website design, Frontend design, more. </p>
            <div class="home-sci">
                <a href="https://github.com/Shreyasachan003/ABC-College-Website.git"style="--i:7"><i class="bx bxl-linkedin"></i></a>
                <a href="#"style="--i:8"><i class="bx bxl-instagram"></i></a>
                <a href="#"style="--i:9"><i class="bx bxl-twitter"></i></a>
                <a href="#"style="--i:10"><i class="bx bxl-github"></i></a>
            </div>
            <a href="#about" class="btn-box">More About Me</a>
        </div>
    <span class="home-imgHover"></span>
    </section>

    <section class="about" id="about">
        <div class="about-img">
            <img src="Group 1.png">
        </div>
        <div class="about-text">
            <h2>About<span>Me</span></h2>
            <h4>Full Stack Developer!</h4>
            <p>I have one and half years of experience working in the field of Web development,with a strong knowledge of HTML,CSS,Javascript. My expertise extends to Python as wll,broadening my capabilities as a adeveloper. Additionally ,I possess project management skills ,enabling i efficiently oversee and coordinate tasks and teams.</p>
            <a href="#" class="btn-box">More About Me</a>
        </div>
    </section>

    <section>
        <div class="services" id="services">
            <div class="container">
                <h1 class="sib-title">My <span>Services</span></h1>
                <div class="services-list">
                    <div>
                        <i class="bx bx-code" style="color: crimson"></i>
                        <h2>Web developer</h2>
                        <p>As a web developer proficient in HTML, CSS, and JavaScript, I have hands-on experience in building and maintaining web applications. I have completed several projects that demonstrate my ability to create responsive, user-friendly, and visually appealing websites.</p>
                        <a href="#" class="read">Learn more</a>
                    </div>
                    <div>
                        <i class="bx bx-crop" style="color: crimson"></i>
                        <h2>UI/UX Designer</h2>
                        <p>A passionate UI/UX designer with a keen eye for creating intuitive and visually stunning digital experiences.With expertise in Canva ,figma ,Invision and sketch,I craft user-centered designes that drive engagement and conversion.</p>
                        <a href="#" class="read">Learn more</a>
                    </div>
                    <!---<div>
                        <i class='bx bxl-apple'style="color: crimson"></i>
                        <h2>UI/UX Design</h2>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore aspernatur recusandae accusamus numquam, voluptates quos sequi officiis provident, incidunt dignissimos ut perferendis dolore non aliquam quam nam est modi praesentium.</p>
                        <a href="#" class="read">Learn more</a>
                    </div>-->
                </div>
            </div>
        </div>
    </section>
    <h1 class="sub-title">My <span>Skills</span></h1>

    <section>
        <div class="container1" id="Skills">
            <h1 class="heading1">Technical Skills</h1>
            <div class="Technical-bars">
                <div class="bar"><i style="color: crimson" class="bx bxl-html5"></i>
                    <div class="info">
                        <span>HTML</span>
                    </div>
                    <div class="progress-line html">
                        <span>  </span>
                    </div>
                </div>
                <div class="bar"><i style="color: crimson" class="bx bxl-css3"></i>
                    <div class="info">
                        <span>CSS</span>
                    </div>
                    <div class="progress-line css">
                        <span>  </span>
                    </div>
                </div>
                <div class="bar"><i style="color: crimson" class="bx bxl-javascript"></i>
                    <div class="info">
                        <span>JavaScript</span>
                    </div>
                    <div class="progress-line javascript">
                        <span>  </span>
                    </div>
                </div>
                <div class="bar"><i style="color: crimson" class="bx bxl-python"></i>
                    <div class="info">
                        <span>Python</span>
                    </div>
                    <div class="progress-line python">
                        <span>  </span>
                    </div>
                </div>
                <!--<div class="bar"><i style="color: crimson" class="bx bxl-react"></i>
                    <div class="info">
                        <span>react</span>
                    </div>
                    <div class="progress-line react">
                        <span>  </span>
                    </div>
                </div>-->
            </div>
        </div>

        <div class="container1">
            <h1 class="heading1">Professional Skills</h1>
            <div class="radial-bars">

                <div class="radial-bar">
                    <svg x="0px" y="0px" viewBox="0 0 200 200">
                        <circle class="progress-bar" cx="100" cy="100" r="80"></circle>
                        <circle class="path path-1" cx="100" cy="100" r="80"></circle>
                    </svg>
                   <div class="percentage">90%</div>
                   <div class="text">Creativity</div>
                </div>
                <div class="radial-bar">
                    <svg x="0px" y="0px" viewBox="0 0 200 200">
                       <circle class="progress-bar" cx="100" cy="100" r="80"></circle>
                       <circle class="path path-2" cx="100" cy="100" r="80"></circle>
                    </svg>
                   <div class="percentage">70%</div>
                   <div class="text">Communication</div>
                </div>
                <div class="radial-bar">
                    <svg x="0px" y="0px" viewBox="0 0 200 200">
                       <circle class="progress-bar" cx="100" cy="100" r="80"></circle>
                       <circle class="path path-3" cx="100" cy="100" r="80"></circle>
                    </svg>
                   <div class="percentage">65%</div>
                   <div class="text">Problem Solving</div>
                </div>
                <div class="radial-bar">
                    <svg x="0px" y="0px" viewBox="0 0 200 200">
                        <circle class="progress-bar" cx="100" cy="100" r="80"></circle>
                        <circle class="path path-4" cx="100" cy="100" r="80"></circle>
                    </svg>
                   <div class="percentage">90%</div>
                   <div class="text">TeamWork</div>
                </div>
            </div>    
        </div>
    </section>
    
    <section>
        <div id="portfolio" id="project">
            <div class="main-text" id="project">
                <h2>Latest <span>Project</span></h2>

                <div class="portfolio-content">
                    <div class="row">
                        <img src="abc college.png">
                        <div class="layer">
                            <h5>College Website</h5>
                            <P>I recently developed a comprehensive college website designed to serve as an all-in-one resource for students, faculty, staff, and prospective students.</P>

                            <a href="https://github.com/Shreyasachan003/ABC-College-Website.git"><i class='bx bx-link-external' style="color: black";></i></a>
                        </div>
                    </div>

                    <div class="row">
                        <img src="int.png">
                        <div class="layer">
                            <h5>Interior designer Website</h5>
                            <P>The interior design website I created is designed to provide a visually appealing, user-friendly, and informative platform for showcasing design projects, offering inspiration, and connecting with potential clients</P>

                            <a href="https://github.com/Shreyasachan003/interior-designing-website.git"><i class='bx bx-link-external' style="color: black";></i></a>
                        </div>
                    </div>

                    <div class="row">
                        <img src="gal.png">
                        <div class="layer">
                            <h5>Image Gallery</h5>
                            <P>Explore our gallery where you get every and each type of pictures you want for your work or projects.Every can use this image gallery its having very simple and minimal interface so anyone can use this gallery very easily.</P>

                            <a href="https://github.com/Shreyasachan003/Igon.git"><i class='bx bx-link-external' style="color: black";></i></a>
                        </div>
                    </div>

                    <div class="row">
                        <img src="d74c78bedc07ce521f50c9805c9f256de5bdac09-1200x628.webp">
                        <div class="layer">
                            <h5></h5>
                            <P></P>

                            <a href="#"><i class='bx bx-link-external' style="color: black";></i></a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="contact" id="contact">
        <div class="contact-text">
            <h2>Contact <span>Me</span></h2>
            <h4>Let's work Together</h4>
            <p> Lorem ipsum dolor sit amet consectetur adipisicing 
                elit. Unde illo quae illum eveniet! A minima ullam 
                laudantium repellat quaerat animi neque repudiandae 
                minus. Quo reprehenderit quod deleniti tempora nemo 
                quam</p>
                <div class="contact-list">
                    <li><i class="bx bxs-send"></i>contact@gmail.com</li>
                    <li><i class="bx bxs-phone"></i>0123456789</li>
                </div>
                <div class="contact-icons">
                    <a herf=""><i class="bx bxl-facebook-circle"></i></a>
                    <a herf=""><i class="bx bxl-twitter"></i></a>
                    <a herf=""><i class="bx bxl-instagram"></i></a>
                    <a herf=""><i class="bx bxl-linkedin"></i></a>
                </div>
        </div>

        <div class="contact-form">
            <form action="">
                <input type="" placeholder="Enter Your Name" required>
                <input type="email" placeholder="Enter Your Email" required>

                <input type="" placeholder="Enter Your Subject">
                <textarea name="" id="" cols="40" rows="10" placeholder="Enter Your Message" required></textarea>
            <input type="submit" value="submit" class="send">
            </form>
        </div>
    </section>
    <div class="last-text">
        <p>Developed with love by Shreya Sachan</p>
    </div>
    <a href="#" class="top"><i class="bx bx-up-arrow-alt"></i></a>

    <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
    <script>
        var typed = new Typed('.text', {
            strings: ["Frontend Developer", "Web Developer"],
            typeSpeed: 100,
            backSpeed: 100,
            backDelay: 1000,
            loop: true
        });
    </script>
    
</body>
</html>
