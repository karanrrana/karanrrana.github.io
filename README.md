<!DOCTYPE html>
<html class="no-js" lang="en">

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>My Portfolio</title>
	<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
	<link rel="icon" href="favicon.ico" type="image/x-icon">
    <link href="https://fonts.googleapis.com/css?family=Lato:300,400,700,900" rel="stylesheet">
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
            <h1>Karan Rana</h1>
            <h2>Software Engineer</h2>
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
                        Throughout middle and high school, I latched on to any ideas for projects I could get, moving from "Hello World" all the way to a simple First Person Shooter engine, with dozens of projects in between. I learned C, then C++, tearing through any books I could find on anything remotely related to software development.
                    </p>
                </div>
            </div>
        </div>
    </div>
    <!-- End #about -->

    <div id="experience" class="background-alt">
        <h2 class="heading">Experience</h2>
        <div id="experience-timeline">
            <div data-date="January 2021 - February 2021">
                <h3>Complere Infosystem</h3>
                <h4>Intern</h4>
                <p>
                    Gathered, analysed, and interpreted data from clients and partners using vast databases and a variety of expert statistical approaches.
            </div>

            <div data-date="December 2021 – March 2022">
                <h3>SEOXPORT</h3>
                <h4>SEO Specialist</h4>
                <p>
                    Developed and executed interactive marketing strategies for roughly 15 companies that increased traffic to websites, enhanced search engine performance, and stimulated growth. As a consequence, there was an average 23% increase in yearly traffic year over year. data was analysed to find trends, create reports, and change campaigns as needed to provide the best ROI.
                </p>
            </div>

            <!-- <div data-date="September 2015 – September 2016">
                <h3>Employer Name</h3>
                <h4>Job Title</h4>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur in iaculis ex. Etiam volutpat laoreet urna. Morbi ut tortor nec nulla commodo malesuada sit amet vel lacus. Fusce eget efficitur libero. Morbi dapibus porta quam laoreet placerat.
                </p>
            </div> -->
        </div>
    </div>
    <!-- End #experience -->

    <div id="education">
        <h2 class="heading">Education</h2>
        <div class="education-block">
            <h3>Kalinga University</h3>
            <span class="education-date">2019 - 2021</span>
            <h4>Bachelor of Science in Computer Science</h4>
            <p>
                To succeed in an IT career, you must possess strong computer and technological abilities. This can include having a solid grasp of operating systems, keyboarding skills, and expertise with spreadsheets and presentations. As you advance through your education and graduate from Kalinga University, you acquire all of these essential computer abilities.
            </p>
        </div>
        <!-- End .education-block -->

        <div class="education-block">
            <h3>Jaypee Univeristy of Information Technology</h3>
            <span class="education-date">2021 - 2025</span>
            <h4>Bachelor of Technology in Computer Science</h4>
            <ul>
                Skills Gained:
                <li>
                    Working level knowledge of C, C++, Java, HTML, JavaScript, Python.
                </li>
                <li>
                    Strong understanding of Algorithms.
                </li>
                <li>
                    Stong understanding of Number theory, Set theory, Relations and Functions, Matrix Theory, Boolean Algebra and Descrete Mathematics.
                </li>
                <li>
                    Functional level knowledge of computer hardware and how it interacts with the other devices within and outside the computer.
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
                        <img src="images/project.jpg" />
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>Music Player</h3>
                        <p>
                            It is a Graphical User Interface of a Music Player made using python and its libraries that are Tkinter, Pygame, Mutagen etc.
                        </p>
                        <a href="https://github.com/karanrrana/Music-player">View Project</a>
                    </div>
                    <!-- End .project-info -->
                </div>
                <!-- End .project -->

                <div class="project shadow-large">
                    <div class="project-image">
                        <img src="images/project.jpg" />
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>Bookshop Manager</h3>
                        <p>
                            It is a basic C++ program for Bookshop management system made using fundamental principles of C++.
                        </p>
                        <a href="https://github.com/karanrrana/Bookshop-manager">View Project</a>
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
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>React</li>
            <li>C</li>
            <li>C#</li>
            <li>C++</li>
            <li>PHP</li>
            <li>Python</li>
            <li>Django</li>
        </ul>
    </div>
    <!-- End #skills -->

    <div id="contact">
        <h2>Get in Touch</h2>
        <div id="contact-form">
            <form method="POST" action="https://formspree.io/f/mdovzvov">
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
                        Copyright &copy; <span id="current-year">2022</span> KARAN RANA
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
                            <a href="https://github.com/karanrrana" target="_blank"><i class="fa fa-github" aria-hidden="true"></i></a>
                        </li>
                        <!-- <li>
                            <a href="https://stackoverflow.com/" target="_blank"><i class="fa fa-stack-overflow" aria-hidden="true"></i></a>
                        </li> -->
                        <li>
                            <a href="https://www.linkedin.com/in/karan-rana-970393208/" target="_blank"><i class="fa fa-linkedin" aria-hidden="true"></i></a>
                        </li>
                        <!-- <li>
                            <a href="https://www.facebook.com/" target="_blank"><i class="fa fa-facebook" aria-hidden="true"></i></a>
                        </li> -->
                        <li>
                            <a href="https://twitter.com/zptoxic_" target="_blank"><i class="fa fa-twitter" aria-hidden="true"></i></a>
                        </li>
                        <li>
                            <a href="mailto:karan.rana6582@gmail.com" target="_blank"><i class="fa fa-google-plus" aria-hidden="true"></i></a>
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
