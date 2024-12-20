<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hari Hara Sudan's Profile</title>
    <link rel="stylesheet" href="styles.css">
    <!-- AOS Animation Library -->
    <link href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css" rel="stylesheet">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
        }

        .container {
            width: 90%;
            margin: 0 auto;
            padding-top: 40px;
        }

        h1,
        h2 {
            text-align: center;
        }

        section {
            margin: 30px 0;
        }

        .intro h1 {
            font-size: 2.5rem;
            color: #4CAF50;
        }

        .about p {
            font-size: 1.2rem;
            color: #666;
            text-align: center;
        }

        .skills {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
            gap: 20px;
            text-align: center;
        }

        .tech-icons img {
            width: 50px;
            height: 50px;
            margin: 10px;
            transition: transform 0.3s ease-in-out;
        }

        .tech-icons img:hover {
            transform: scale(1.1);
        }

        .tech-icons {
            display: flex;
            justify-content: center;
            gap: 20px;
            align-items: center;
        }

        .contact-info {
            text-align: center;
            margin-top: 20px;
        }

        .contact-info a {
            color: #4CAF50;
            text-decoration: none;
            font-weight: bold;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        /* AOS Animation */
        .intro,
        .skills,
        .contact-info {
            animation: fadeInUp 1s ease-in-out;
        }

        @keyframes fadeInUp {
            0% {
                opacity: 0;
                transform: translateY(20px);
            }

            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>

<body>

    <div class="container">
        <!-- Intro Section -->
        <section class="intro" data-aos="fade-up">
            <h1>Hello, I'm Hari Hara Sudan 👨🏻‍💻</h1>
            <p>I'm an AI & ML enthusiast and a passionate web developer from Coimbatore, Tamil Nadu, India. I enjoy creating impactful solutions with a blend of machine learning and full-stack development.</p>
        </section>

        <!-- About Section -->
        <section class="about" data-aos="fade-right">
            <p>I'm dedicated to exploring AI, solving real-world problems, and building projects that matter. Let's innovate together!</p>
        </section>

        <!-- Technologies & Tools -->
        <section class="skills" data-aos="fade-left">
            <h2>Technologies & Tools</h2>
            <div class="tech-icons">
                <!-- Languages -->
                <div class="languages">
                    <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg" title="Python" alt="Python" />
                    <img src="https://github.com/devicons/devicon/blob/master/icons/java/java-original.svg" title="Java" alt="Java" />
                    <img src="https://github.com/devicons/devicon/blob/master/icons/c/c-original.svg" title="C" alt="C" />
                    <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML5" />
                    <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-original.svg" title="CSS3" alt="CSS3" />
                    <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" />
                </div>

                <!-- Frameworks -->
                <div class="frameworks">
                    <img src="https://github.com/devicons/devicon/blob/master/icons/flask/flask-original.svg" title="Flask" alt="Flask" />
                    <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original.svg" title="ReactJS" alt="ReactJS" />
                </div>

                <!-- Databases -->
                <div class="databases">
                    <img src="https://github.com/devicons/devicon/blob/master/icons/mysql/mysql-original-wordmark.svg" title="MySQL" alt="MySQL" />
                    <img src="https://github.com/devicons/devicon/blob/master/icons/firebase/firebase-plain.svg" title="Firebase" alt="Firebase" />
                </div>

                <!-- Tools -->
                <div class="tools">
                    <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original.svg" title="Git" alt="Git" />
                    <img src="https://github.com/devicons/devicon/blob/master/icons/github/github-original.svg" title="GitHub" alt="GitHub" />
                    <img src="https://github.com/devicons/devicon/blob/master/icons/selenium/selenium-original.svg" title="Selenium" alt="Selenium" />
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section class="contact-info" data-aos="fade-up">
            <p>Feel free to reach out to me:</p>
            <p>
                <a href="mailto:hariharasudan.dev@gmail.com">📧 Email Me</a> | 
                <a href="https://www.linkedin.com/in/hari-hara-sudan" target="_blank">🌐 LinkedIn</a>
            </p>
        </section>
    </div>

    <!-- AOS Script -->
    <script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>
    <script>
        AOS.init({
            offset: 100, // offset (in px) from the original trigger point
            duration: 600, // animation duration in ms
            easing: 'ease-in-out', // easing function
            delay: 0, // delay in ms
        });
    </script>
</body>

</html>
