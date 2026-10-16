# portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>My Portfolio | IT Student</title>

    <style>
        /* CSS: General Styling */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #2b0202;
            color: white;
            line-height: 1.6;
        }

        header {
            background-color: #4a0404;
            padding: 20px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 15px;
        }

        header h1 {
            color: #FFD700;
            font-size: 25px;
        }

        nav {
            display: flex;
            flex-wrap: wrap;
            gap: 18px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover,
        nav a:focus {
            color: #FFD700;
        }

        section {
            padding: 60px 10%;
            scroll-margin-top: 20px;
        }

        h2 {
            color: #FFD700;
            text-align: center;
            margin-bottom: 25px;
            font-size: 30px;
        }

        /* Home Section */
        .home {
            min-height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        .home h2 {
            font-size: 38px;
            margin-bottom: 10px;
        }

        .home p {
            font-size: 18px;
            max-width: 650px;
        }

        .button {
            display: inline-block;
            background-color: #FFD700;
            color: #2b0202;
            padding: 12px 25px;
            margin-top: 20px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            border: none;
            cursor: pointer;
        }

        .button:hover,
        .button:focus {
            background-color: white;
        }

        /* About Section */
        .about {
            background-color: #4a0404;
            text-align: center;
        }

        .about p {
            max-width: 750px;
            margin: auto;
        }

        /* Education and Skills */
        .container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
            gap: 20px;
        }

        .card {
            background-color: #4a0404;
            border: 1px solid #FFD700;
            padding: 25px;
            border-radius: 10px;
            text-align: center;
        }

        .card h3 {
            color: #FFD700;
            margin-bottom: 12px;
        }

        .card p {
            margin-bottom: 8px;
        }

        /* Projects Section */
        .projects {
            background-color: #4a0404;
        }

        /* Contact Section */
        .contact {
            text-align: center;
        }

        .contact a {
            color: #FFD700;
        }

        footer {
            background-color: #4a0404;
            text-align: center;
            padding: 20px;
            border-top: 1px solid #FFD700;
        }

        /* JavaScript Message */
        #message {
            color: #FFD700;
            margin-top: 15px;
            font-weight: bold;
        }

        /* Responsive Design */
        @media (max-width: 600px) {
            header {
                flex-direction: column;
                text-align: center;
            }

            nav {
                justify-content: center;
                gap: 12px;
            }

            section {
                padding: 40px 6%;
            }

            .home h2 {
                font-size: 28px;
            }

            h2 {
                font-size: 25px;
            }

            .home p {
                font-size: 16px;
            }
        }
    </style>
</head>

<body>

    <!-- Header and Navigation -->
    <header>
        <h1>My Portfolio</h1>

        <nav aria-label="Main navigation">
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#education">Education</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>

        <!-- Home Section -->
        <section id="home" class="home">
            <h2>Hello, I'm Diya Rabari</h2>

            <p>
                Welcome to my portfolio! I am a B.Sc. IT student
                interested in web development, databases, and technology.
                I enjoy learning new skills and creating useful projects.
            </p>

            <a href="#projects" class="button">View My Projects</a>

            <button type="button" class="button" id="welcomeButton">
                Click Me
            </button>

            <p id="message" aria-live="polite"></p>
        </section>

        <!-- About Section -->
        <section id="about" class="about">
            <h2>About Me</h2>

            <p>
                I am an enthusiastic Information Technology student
                who enjoys learning programming and exploring new
                technologies. My goal is to improve my technical skills
                and build a successful career in the IT industry.
                I believe in continuous learning and personal growth.
            </p>
        </section>

        <!-- Education Section -->
        <section id="education">
            <h2>My Education</h2>

            <div class="container">

                <article class="card">
                    <h3>B.Sc. Information Technology</h3>
                    <p>CHARUSAT University</p>
                    <p>Currently Studying</p>
                </article>

                <article class="card">
                    <h3>12th Standard</h3>
                    <p>GSEB Board</p>
                    <p>Percentage: 89.23%</p>
                    <p>Year: 2025</p>
                </article>

                <article class="card">
                    <h3>10th Standard</h3>
                    <p>GSEB Board</p>
                    <p>Percentage: 88%</p>
                    <p>Year: 2023</p>
                </article>

            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="about">
            <h2>My Skills</h2>

            <div class="container">

                <article class="card">
                    <h3>Programming</h3>
                    <p>C++</p>
                    <p>HTML</p>
                    <p>CSS</p>
                </article>

                <article class="card">
                    <h3>Database</h3>
                    <p>MySQL</p>
                    <p>SQL Queries</p>
                    <p>Database Management</p>
                </article>

                <article class="card">
                    <h3>Other Skills</h3>
                    <p>Microsoft Excel</p>
                    <p>Problem Solving</p>
                    <p>Time Management</p>
                </article>

            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="projects">
            <h2>My Projects</h2>

            <div class="container">

                <article class="card">
                    <h3>Personal Portfolio</h3>
                    <p>
                        A personal website created using HTML,
                        CSS, and JavaScript.
                    </p>
                </article>

                <article class="card">
                    <h3>Web Design Project</h3>
                    <p>
                        A basic web page created using HTML
                        and CSS to practice web development.
                    </p>
                </article>

                <article class="card">
                    <h3>Database Project</h3>
                    <p>
                        SQL queries and database operations
                        created as part of my IT coursework.
                    </p>
                </article>

            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="contact">
            <h2>Contact Me</h2>

            <p>
                Thank you for visiting my portfolio!
            </p>

            <p>
                Email:
                <a href="mailto:yourname@example.com">
                    yourname@example.com
                </a>
            </p>

            <p>
                Location: Gujarat, India
            </p>

            <a href="#home" class="button">Back to Home</a>
        </section>

    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 Diya Rabari | My Portfolio</p>
    </footer>

    <script>
        // JavaScript: Interactive Welcome Button
        const welcomeButton = document.getElementById("welcomeButton");
        const message = document.getElementById("message");

        welcomeButton.addEventListener("click", function () {
            message.textContent =
                "Thank you for visiting my portfolio! Have a great day.";

            welcomeButton.textContent = "Thank You!";
        });
    </script>

</body>
</html>
