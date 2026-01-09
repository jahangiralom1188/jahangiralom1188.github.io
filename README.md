<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Jahangir Alom | About Me</title>

    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Jahangir Alom – Computer Science Engineering student, aspiring developer, and music enthusiast.">

    <style>
        body {
            margin: 0;
            font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
            background: #0f172a;
            color: #e5e7eb;
        }

        /* HERO SECTION */
        .hero {
            text-align: center;
            padding: 70px 20px;
            background: linear-gradient(135deg, #2563eb, #1e40af);
        }

        .hero img {
            width: 170px;
            height: 170px;
            border-radius: 50%;
            border: 5px solid white;
            object-fit: cover;
            margin-bottom: 20px;
        }

        .hero h1 {
            margin: 0;
            font-size: 42px;
        }

        .hero p {
            font-size: 18px;
            margin-top: 10px;
            opacity: 0.9;
        }

        /* MAIN CONTAINER */
        .container {
            max-width: 1000px;
            margin: auto;
            padding: 30px 20px;
        }

        section {
            background: #020617;
            padding: 30px;
            border-radius: 14px;
            margin-bottom: 30px;
            box-shadow: 0 15px 40px rgba(0,0,0,0.4);
        }

        h2 {
            margin-top: 0;
            font-size: 26px;
            border-bottom: 2px solid #2563eb;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }

        p {
            font-size: 16px;
            line-height: 1.7;
        }

        /* HIGHLIGHT CARDS */
        .cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
        }

        .card {
            background: linear-gradient(135deg, #1e293b, #020617);
            padding: 25px;
            border-radius: 12px;
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .card:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 50px rgba(37,99,235,0.4);
        }

        .card h3 {
            margin-bottom: 10px;
            color: #60a5fa;
        }

        /* LIST */
        ul {
            padding-left: 20px;
        }

        li {
            margin-bottom: 8px;
        }

        /* CONTACT */
        a {
            color: #60a5fa;
            text-decoration: none;
            font-weight: 500;
        }

        a:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #020617;
            color: #9ca3af;
            font-size: 14px;
        }
    </style>
</head>

<body>

<!-- HERO PROFILE -->
<section class="hero">
    <img src="IMG20220608162923.jpg" alt="Jahangir Alom Profile Photo">
    <h1>Jahangir Alom</h1>
    <p>Computer Science Engineering Student • Aspiring Developer • Music Lover</p>
</section>

<div class="container">

    <!-- ABOUT ME -->
    <section>
        <h2>About Me</h2>
        <p>
            Hello! I’m <strong>Jahangir Alom</strong>, a passionate and motivated
            <strong>Computer Science Engineering student</strong> with a deep interest
            in programming, web development, and modern technologies.
        </p>

        <p>
            I have successfully completed a
            <strong>Post Graduate Diploma in Computer Applications (PGDCA)</strong>,
            where I gained one year of structured hands-on training in computer systems,
            software tools, and programming fundamentals.
        </p>

        <p>
            I enjoy solving problems, learning new technologies, and continuously
            improving my skills to become a professional software developer.
        </p>
    </section>

    <!-- PROFILE HIGHLIGHTS -->
    <section>
        <h2>My Profile</h2>
        <div class="cards">
            <div class="card">
                <h3>🎓 Student</h3>
                <p>
                    Currently pursuing Computer Science Engineering with a strong academic
                    foundation in computing and programming.
                </p>
            </div>

            <div class="card">
                <h3>💻 Developer</h3>
                <p>
                    Building projects using HTML, CSS, and core programming concepts.
                    Passionate about clean and user-friendly design.
                </p>
            </div>

            <div class="card">
                <h3>🎸 Musician</h3>
                <p>
                    Guitar player with 1.5 years of experience.
                    Music fuels my creativity and focus.
                </p>
            </div>
        </div>
    </section>

    <!-- SKILLS -->
    <section>
        <h2>Skills & Interests</h2>
        <ul>
            <li>HTML & CSS (Web Development)</li>
            <li>Programming & Logical Thinking</li>
            <li>Problem Solving</li>
            <li>Guitar Playing & Music</li>
            <li>Continuous Learning</li>
        </ul>
    </section>

    <!-- CONTACT -->
    <section>
        <h2>Contact Me</h2>
        <ul>
            <li>📞 <a href="tel:+917637861188">+91 7637861188</a></li>
            <li>📧 <a href="mailto:ja3174257@gmail.com">ja3174257@gmail.com</a></li>
            <li>💬 <a href="https://wa.me/917637861188" target="_blank">Chat on WhatsApp</a></li>
            <li>📍 Abhayapuri, Bongaigaon, Assam, India</li>
        </ul>
    </section>

</div>

<footer>
    <p>© 2026 Jahangir Alom | Personal Portfolio</p>
</footer>

</body>
</html>
