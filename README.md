<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="styles.css">
    <style>
        .project-card {
            position: relative;
            overflow: hidden;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .project-card img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        .project-card .card-body {
            position: absolute;
            bottom: 0;
            background-color: rgba(0, 0, 0, 0.6);
            color: white;
            width: 100%;
            padding: 15px;
            opacity: 0;
            transition: opacity 0.3s;
        }
        .project-card:hover .card-body {
            opacity: 1;
        }
        .project-card .card-body h5 {
            font-size: 1.2rem;
        }
        .project-card .card-body p {
            font-size: 0.9rem;
        }

    </style>
</head>
<body>

    <!-- Navigation Section -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#"><img src="images/logo.PNG" alt="" width="30" height="24" class="d-inline-block align-text-top">
                My Portfolio</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>
    <!-- End Navigation Section -->

    <!-- Header Section -->
    <header class="jumbotron text-center" style="background-image: url('images/header2.PNG'); height: 300px; background-size: cover; opacity: 7; background-position: center; color: cyan;">
        <div class="container">
            <h1 class="display-4">Hello, welcome to my portfolio</h1>
            <p>I'm thrilled to have you here. Explore my journey in design, development, and creativity.</p>
            <p>I help businesses and individuals bring their ideas to life.</p>
            <p class="lead">Code it. Build it. Scale it. Master the stack.</p>
            <a href="#projects" class="btn btn-primary btn-lg">View my Work</a>
        </div>
    </header>
<!-- Header Section -->

<!-- About Section  start-->
    <section id="about" class="py-5">
        <div class="container">
            <div class="row">
                <div class="col-lg-6">
                    <h2>Who am I ?</h2>
                    <p>
                        Hi, I’m Bridget Wachira, a versatile Full Stack Developer passionate about building end-to-end solutions that are both functional and visually appealing. With expertise in frontend and backend technologies, I specialize in creating seamless user experiences powered by robust and scalable systems.

                        I thrive on solving complex problems and turning ideas into innovative applications. My skill set includes HTML, CSS, JavaScript, and frameworks like Bootstrap for designing intuitive interfaces, alongside backend tools and databases for managing dynamic content and efficient data handling.

                        I’m committed to continuous learning and exploring new technologies, including cloud computing and DevOps, to deliver modern, future-ready applications. Whether it's developing a web app, optimizing a system, or designing a captivating user interface, I’m here to bring visions to life.

                        Let’s build something extraordinary together!
                    </p>
                </div>
                <div class="col-lg-6">
                    <img src="images/me.jpg" alt="My Picture" class="img-fluid " >
                </div>
            </div>
        </div>
    </section>
<!--about section end-->
<!--project section-->
<section id="projects" class="py-5">
    <div class="container py-5">
        <h2>Featured Projects</h2>
     <div class="row row-cols-1 row-cols-md-3 g-4">
         <div class="col">
             <div class="card project-card">
                 <img src="images/h1.jpg" class="card-img-top" alt="Project 1">
                 <div class="card-body">
                     <h5 class="card-title">Project 1: Web App</h5>
                     <p class="card-text">A dynamic web application built using HTML, CSS, and JavaScript.</p>
                     <a href="project1.html" class="btn btn-light">View Details</a>
                 </div>
             </div>
         </div>
         <div class="col">
             <div class="card project-card">
                 <img src="images/header1.PNG" class="card-img-top" alt="Project 2">
                 <div class="card-body">
                     <h5 class="card-title">Project 2: Mobile App</h5>
                     <p class="card-text">A mobile app designed for seamless user experiences with React Native.</p>
                     <a href="project2.html" class="btn btn-light">View Details</a>
                 </div>
             </div>
         </div>
         <div class="col">
             <div class="card project-card">
                 <img src="images/header2.PNG" class="card-img-top" alt="Project 3">
                 <div class="card-body">
                     <h5 class="card-title">Project 3: E-commerce Site</h5>
                     <p class="card-text">An e-commerce website built with Django and integrated payment systems.</p>
                     <a href="project3.html" class="btn btn-light">View Details</a>
                 </div>
             </div>
         </div>
 
     </div>
 </div>
 </section>
 <!--    project section end-->

<!-- Contact Section -->
<section id="contact" class="py-5 p-5">
       <div class="container py-5 text-center">
            <h2>Contact Me</h2>
            <p>If you'd like to get in touch, feel free to reach out via email or through social media:</p>

           <ul class="list-unstyled d-flex justify-content-center flex-column align-items-center">
                <li><strong>Email:</strong> <a href="mailto:wanjirubridget10@gmail.com">wanjirubridget10@gmail.com</a></li>

                <li><strong>Phone:</strong> <a href="tel:+254741791091">+254741791091</a></li>

                <li><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/bridget-wachira-48b928265/" target="_blank">linkedin.com/in/yourprofile</a></li>
                <li><strong>GitHub:</strong> <a href="https://github.com/wachirabridget/" target="_blank">github.com/wachirabridget</a></li>
            </ul>

            <h4>Contact via WhatsApp:</h4>
            <a href="https://wa.me/+254741791091" target="_blank" class="btn btn-info mb-4">Chat with me on WhatsApp</a>

            <h4>Download My Resume</h4>
            <a href="BRIDGET_WANJIRU (2).docx" class="btn btn-info" download>Download Resume (PDF)</a>
        </div>


</section>
<!--    contact section end-->

    <!-- Footer Section -->
<footer class="bg-dark text-white text-center py-4"  >
        <div class="container">
            <p>&copy; 2024 My Portfolio.bridget.</p>
            <p>Follow me on:
            <a href="https://www.linkedin.com/in/bridget-wachira-48b928265/" class="text-white ml-2">LinkedIn</a> |
            <a href="https://github.com/wachirabridget/" class="text-white ml-2">GitHub</a>
            </p>
                <a href="term.html">Terms of Service</a> |
                <a href="privacy.html">Privacy Policy</a> |
                <a href="#top" class="btn btn-link">Back to Top</a>
            </p>
        </div>
</footer>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
## Overview

Welcome to my portfolio! This website showcases my skills, projects, and expertise as a Full Stack Developer. It features a user-friendly design, interactive elements, and a responsive layout to highlight my journey in web and mobile development.

## Features

- **Modern UI/UX**: A visually appealing interface with smooth animations and a structured layout.
- **Responsive Design**: Fully optimized for desktops, tablets, and mobile devices.
- **Projects Showcase**: Highlights key projects with images, descriptions, and links for more details.
- **Contact Section**: Provides multiple ways to connect with me, including email, phone, WhatsApp, and LinkedIn.
- **Resume Download**: Allows visitors to download my latest resume.
- **Interactive Navigation**: Smooth scrolling and a user-friendly experience.

## Technologies Used

- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: Django (for database-driven projects)
- **Database**: PostgreSQL (for data management in full-stack applications)
- **Version Control**: Git and GitHub for project tracking and collaboration
- **Hosting**: Deployed using GitHub Pages and cloud services for backend functionality

## How to Use

1. Open the portfolio website 
2. Navigate through the sections using the top menu.
3. Click on project images or buttons to explore more details.
4. Use the contact section to connect with me.
5. Download my resume if needed.

## Contact

- **Email**: [wanjirubridget10@gmail.com](mailto\:wanjirubridget10@gmail.com)
- **Phone**: [+254741791091](tel:+254741791091)
- **LinkedIn**: [Bridget Wachira](https://www.linkedin.com/in/bridget-wachira-48b928265/)
- **GitHub**: [wachirabridget](https://github.com/wachirabridget)

## Contribution

If you have suggestions for improving this portfolio, feel free to fork the repository, make changes, and submit a pull request.

## License

This project is open-source and available under the MIT License.

## Acknowledgments

A special thanks to everyone who has supported my web and software development journey!

