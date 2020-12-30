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
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur in iaculis ex. Etiam volutpat
                        laoreet urna. Morbi ut tortor nec nulla commodo malesuada sit amet vel lacus. Fusce eget efficitur
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
            <div data-date="February 2020 – December 2020">
                <h3>Bonna inc.</h3>
                <h4>Software Developer</h4>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur in iaculis ex. Etiam volutpat
                    laoreet urna. Morbi ut tortor nec nulla commodo malesuada sit amet vel lacus. Fusce eget efficitur
                    libero. Morbi dapibus porta quam laoreet placerat.
                </p>
            </div>

            <div data-date="September 2015 – September 2016">
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
            <h4>final project — Coupon management system Grade - 97</h4>
            <ul>
                <li>
                    Back-end: Spring Boot backend working with MSSQL and MySql through JPA.
                    Front-end: Angular 6 + Bootstrap single page application with a login page and a custom design for
                    each
                    end user type.
                </li>
                <li>
                    All basic functionalities for admin, company and customer.
                    Security filters and math utilities.
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
                <li>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                </li>
                <li>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
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
                        <img src="images/funk.gif" />
                    </div>
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
                        <img src="images/space.gif" />
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
                        <img src="images/knowledge.gif" />
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>Knowledge</h3>
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
                        <img src="images/nova.gif" />
                    </div>
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
                        <img src="images/run.gif" />
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
                <!-- End .project -->
            </div>

        </div>
    </div>
    <!-- End #projects -->

    <div id="skills">
        <h2 class="heading">Skills</h2>
        <ul>
            <li>JavaScript</li>
            <li>Python</li>
            <li>Ruby</li>
            <li>Go</li>
            <li>Node.js</li>
            <li>AngularJs</li>
            <li>React</li>
            <li>Elixir</li>
            <li>Java</li>
            <li>C</li>
            <li>C#</li>
            <li>C++</li>
            <li>Ruby on Rails</li>
            <li>JavaScript</li>
            <li>Python</li>
            <li>Ruby</li>
            <li>Go</li>
            <li>Node.js</li>
            <li>AngularJs</li>
            <li>React</li>
            <li>Elixir</li>
            <li>Java</li>
            <li>C</li>
            <li>C#</li>
            <li>C++</li>
            <li>Ruby on Rails</li>
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