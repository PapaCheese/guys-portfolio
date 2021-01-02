<!DOCTYPE html>
<html class="no-js" lang="en">

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>My Portfolio</title>
    <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Rubik:wght@600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="libs/font-awesome/css/font-awesome.min.css">
    <link href="css/bootstrap.min.css" rel="stylesheet">
    <link href="css/styles.css" rel="stylesheet">
</head>

<body>
    <div id="mobile-menu-open" class="shadow-large">
        <i class="fa fa-bars" aria-hidden="true"></i>
    </div>
    <!-- End #mobile-menu-toggle -->
    <header>
        <div id="mobile-menu-close">
            <span>Close</span> <i class="fa fa-times" aria-hidden="true"></i>
        </div>
        <ul id="menu" class="shadow">
            <li>
                <a href="#about">About</a>
            </li>
            <li>
                <a href="#experience">Experience</a>
            </li>
            <li>
                <a href="#education">Education</a>
            </li>
            <li>
                <a href="#projects">Projects</a>
            </li>
            <li>
                <a href="#skills">Skills</a>
            </li>
            <li>
                <a href="#contact">Contact</a>
            </li>
        </ul>
    </header>
    <!-- End header -->

    <div id="lead">
        <div id="lead-content">
            <h1>Guy Dadon</h1>
            <h2>Software Developer</h2>
            <a href="#" class="btn-rounded-white">Download Resume</a>
        </div>
        <!-- End #lead-content -->

        <div id="lead-overlay"></div>

        <div id="lead-down">
            <span>
                <i class="fa fa-chevron-down" aria-hidden="true"></i>
            </span>
        </div>
        <!-- End #lead-down -->
    </div>
    <!-- End #lead -->

    <div id="about">
        <div class="container">
            <div class="row">
                <div class="col-md-4">
                    <h2 class="heading">About Me</h2>
                </div>
                <div class="col-md-8">
                    <p>
                        Born in 1992 (28), Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur in iaculis
                        ex. Etiam volutpat
                        laoreet urna. Morbi ut tortor nec nulla commodo malesuada sit amet vel lacus. Fusce eget
                        efficitur
                        libero. Morbi dapibus porta quam laoreet placerat.
                    </p>
                </div>
            </div>
        </div>
    </div>
    <!-- End #about -->

    <div id="experience" class="background-alt">
        <h2 class="heading">Experience</h2>
        <div id="experience-timeline">
            <div data-date="Jan 2021 – Now">
                <h3>Freelancer</h3>
                <h4>Game Developer</h4>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur in iaculis ex. Etiam volutpat
                    laoreet urna. Morbi ut tortor nec nulla commodo malesuada sit amet vel lacus. Fusce eget efficitur
                    libero. Morbi dapibus porta quam laoreet placerat.
                </p>
            </div>

            <div data-date="April 2020 – Jan 2021">
                <h3>Bonna inc.</h3>
                <h4>Software Developer</h4>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur in iaculis ex. Etiam volutpat
                    laoreet urna. Morbi ut tortor nec nulla commodo malesuada sit amet vel lacus. Fusce eget efficitur
                    libero. Morbi dapibus porta quam laoreet placerat.
                </p>
            </div>

            <div data-date="Aug 2019 – April 2020">
                <h3>Freelancer</h3>
                <h4>Game Developer</h4>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur in iaculis ex. Etiam volutpat
                    laoreet urna. Morbi ut tortor nec nulla commodo malesuada sit amet vel lacus. Fusce eget efficitur
                    libero. Morbi dapibus porta quam laoreet placerat.
                </p>
            </div>


            <div data-date="May 2014 – May 2019">
                <h3>Modiin ezrahi (מודיעין אזרחי)</h3>
                <h4>Security Guard</h4>
                <p>
                    Security guard in the main buildings of social security (ביטוח לאומי).
                </p>
            </div>

        </div>
    </div>
    <!-- End #experience -->

    <div id="education">
        <h2 class="heading">Education</h2>
        <div class="education-block">
            <h3>John Bryce</h3>
            <span class="education-date">November 2017 - January 2019</span>
            <h4>FullStack Java, One year (354 hours)</h4>
            <p>
            <ul>
                <li>
                    Android Studio
                </li>
                <li>
                    OOP, Design Patterns.
                </li>
                <li>
                    Back-end: Java, Spring, MSSQL, MySql, JPA.
                </li>
                <li>
                    Front-end: Angular, Bootstrap, Firebase
                </li>
                <li>
                    Security filters & Math utilities.
                </li>
            </ul>
            </br>
            <h4>Final project — Coupon management system</h4>
            <ul>
                <li>
                    With secure registration.
                </li>
                <li>
                    Grade - 97
                </li>
            </ul>
            </p>
        </div>
        <!-- End .education-block -->

        <div class="education-block">
            <h3>ORT Givat Ram</h3>
            <span class="education-date">Sept 2007 - Sept 2010</span>
            <h4>Electronics & Computer Science</h4>
            <ul>
                <li>
                    High school graduate with electives Electronics and computer science
                    expanding on english translation, C and Java.
                </li>
            </ul>
        </div>
        <!-- End .education-block -->
    </div>
    <!-- End #education -->

    <div id="projects" class="background-alt">
        <h2 class="heading">Projects</h2>
        <div class="container">
            <div class="row">

                <div class="project shadow-large">
                    <div class="project-image">
                        <img src="images/betrailer.gif" />
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info" style="margin-left: 630px;">
                        <h3>Bullet Express</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur in iaculis ex. Etiam
                            volutpat laoreet urna. Morbi ut tortor nec nulla commodo malesuada sit amet vel lacus. Fusce
                            eget efficitur libero. Morbi dapibus porta quam laoreet placerat.
                        </p>
                        <a href="#">View Project</a>
                    </div>
                    <!-- End .project-info -->
                </div>

                <div class="project shadow-large">
                    <div class="project-image">
                        <video width="480" height="270" autoplay loop muted>
                            <source src="images/funk.mp4" type="video/mp4" />
                            Your browser does not support the video tag.
                        </video>                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>Moon Prosody</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur in iaculis ex. Etiam
                            volutpat laoreet urna. Morbi ut tortor nec nulla commodo malesuada sit amet vel lacus. Fusce
                            eget efficitur libero. Morbi dapibus porta quam laoreet placerat.
                        </p>
                        <a href="#">View Project</a>
                    </div>
                    <!-- End .project-info -->
                </div>
                <!-- End .project -->

                <div class="project shadow-large">
                    <div class="project-image">
                        <video width="480" height="270" autoplay loop muted>
                            <source src="images/space2.mp4" type="video/mp4" />
                            Your browser does not support the video tag.
                        </video>
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>COSMONAV</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur in iaculis ex. Etiam
                            volutpat laoreet urna. Morbi ut tortor nec nulla commodo malesuada sit amet vel lacus. Fusce
                            eget efficitur libero. Morbi dapibus porta quam laoreet placerat.
                        </p>
                        <a href="#">View Project</a>
                    </div>
                    <!-- End .project-info -->
                </div>


                <div class="project shadow-large">
                    <div class="project-image">
                        <video width="480" height="270" autoplay loop muted>
                            <source src="images/knowledge.mp4" type="video/mp4" />
                            Your browser does not support the video tag.
                        </video>
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>Knowledge Retention</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur in iaculis ex. Etiam
                            volutpat laoreet urna. Morbi ut tortor nec nulla commodo malesuada sit amet vel lacus. Fusce
                            eget efficitur libero. Morbi dapibus porta quam laoreet placerat.
                        </p>
                        <a href="#">View Project</a>
                    </div>
                    <!-- End .project-info -->
                </div>


                <div class="project shadow-large">
                    <div class="project-image">
                        <video width="480" height="270" autoplay loop muted>
                            <source src="images/nova.mp4" type="video/mp4" />
                            Your browser does not support the video tag.
                        </video>                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>Super Nova</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur in iaculis ex. Etiam
                            volutpat laoreet urna. Morbi ut tortor nec nulla commodo malesuada sit amet vel lacus. Fusce
                            eget efficitur libero. Morbi dapibus porta quam laoreet placerat.
                        </p>
                        <a href="#">View Project</a>
                    </div>
                    <!-- End .project-info -->
                </div>


                <div class="project shadow-large">
                    <div class="project-image">
                        <video width="480" height="270" autoplay loop muted>
                            <source src="images/run.mp4" type="video/mp4" />
                            Your browser does not support the video tag.
                        </video>
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>Dont Stop Running</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur in iaculis ex. Etiam
                            volutpat laoreet urna. Morbi ut tortor nec nulla commodo malesuada sit amet vel lacus. Fusce
                            eget efficitur libero. Morbi dapibus porta quam laoreet placerat.
                        </p>
                        <a href="#">View Project</a>
                    </div>
                    <!-- End .project-info -->
                </div>

                <div class="project shadow-large">
                    <div class="project-image">
                        <video width="480" height="270" autoplay loop muted>
                            <source src="images/anatomy.mp4" type="video/mp4" />
                            Your browser does not support the video tag.
                        </video>
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>Anatomy Mini Game</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur in iaculis ex. Etiam
                            volutpat laoreet urna. Morbi ut tortor nec nulla commodo malesuada sit amet vel lacus. Fusce
                            eget efficitur libero. Morbi dapibus porta quam laoreet placerat.
                        </p>
                        <a href="#">View Project</a>
                    </div>
                    <!-- End .project-info -->
                </div>


                <div class="project shadow-large">
                    <div class="project-image">
                        <video width="480" height="270" autoplay loop muted>
                            <source src="images/math.mp4" type="video/mp4" />
                            Your browser does not support the video tag.
                        </video>
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>Fast Math Mini Game</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur in iaculis ex. Etiam
                            volutpat laoreet urna. Morbi ut tortor nec nulla commodo malesuada sit amet vel lacus. Fusce
                            eget efficitur libero. Morbi dapibus porta quam laoreet placerat.
                        </p>
                        <a href="#">View Project</a>
                    </div>
                    <!-- End .project-info -->
                </div>

                <!-- End .project -->
            </div>

        </div>
    </div>
    <!-- End #projects -->

    <div id="skills">
        <h2 class="heading">Skills</h2>
        <ul>
            <li>Java</li>
            <li>C#</li>
            <li>Python</li>
            <li>Godot Engine</li>
            <li>Unity</li>
            <li>Android Studio</li>
            <li>Node.js</li>
            <li>Angular</li>
            <li>React</li>
            <li>JavaScript</li>
            <li>TypeScript</li>
            <li>HTML</li>
            <li>CSS</li>


        </ul>
    </div>
    <!-- End #skills -->

    <div id="contact">
        <h2>Get in Touch</h2>
        <div id="contact-form">
            <form method="POST" action="https://formspree.io/email@email.com">
                <input type="hidden" name="_subject" value="Contact request from personal website" />
                <input type="email" name="_replyto" placeholder="Your email" required>
                <textarea name="message" placeholder="Your message" required></textarea>
                <button type="submit">Send</button>
            </form>
        </div>
        <!-- End #contact-form -->
    </div>
    <!-- End #contact -->

    <footer>
        <div class="container">
            <div class="row">
                <div class="col-sm-5 copyright">
                    <p>
                        Guy Dadon
                    </p>
                </div>
                <div class="col-sm-2 top">
                    <span id="to-top">
                        <i class="fa fa-chevron-up" aria-hidden="true"></i>
                    </span>
                </div>
                <div class="col-sm-5 social">
                    <ul>
                        <li>
                            <a href="https://github.com/PapaCheese" target="_blank"><i class="fa fa-github"
                                    aria-hidden="true"></i></a>
                        </li>

                        <li>
                            <a href="https://www.linkedin.com/in/guy-dadon-024244167/" target="_blank"><i
                                    class="fa fa-linkedin" aria-hidden="true"></i></a>
                        </li>

                    </ul>
                </div>
            </div>

        </div>
    </footer>
    <!-- End footer -->

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <script src="js/scripts.min.js"></script>
</body>

</html>