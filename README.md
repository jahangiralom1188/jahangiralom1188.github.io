<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Jahangir Alom | Personal Portfolio</title>

    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Jahangir Alom – Computer Science Engineering student, aspiring developer, and music enthusiast.">
    <meta name="author" content="Jahangir Alom">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

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

        /* PROFILE CARDS */
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

        a {
            color: #60a5fa;
            text-decoration: none;
            font-weight: 500;
        }

        a:hover {
            text-decoration: underline;
        }

        /* SOCIAL MEDIA */
        .social-links {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
        }

        .social-links a {
            display: flex;
            align-items: center;
            gap: 10px;
            padding: 12px 22px;
            border-radius: 30px;
            font-weight: 600;
            color: white;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .social-links a i {
            font-size: 18px;
        }

        .instagram {
            background: linear-gradient(45deg, #f58529, #dd2a7b, #8134af);
        }

        .facebook {
            background: #1877f2;
        }

        .fbpage {
            background: #4267B2;
        }

        .social-links a:hover {
            transform: translateY(-6px);
            box-shadow: 0 12px 35px rgba(0,0,0,0.4);
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

<!-- HERO -->
<section class="hero">
    <img src="profile.jpg" alt="Jahangir Alom Profile Photo">
    <h1>Jahangir Alom</h1>
    <p>Computer Science Engineering Student • Aspiring Developer • Music Lover</p>
</section>

<div class="container">

    <!-- ABOUT -->
    <section>
        <h2>About Me</h2>
        <p>
            Hello! I’m <strong>Jahangir Alom</strong>, a Computer Science Engineering student
            with a strong passion for programming, web development, and technology.
        </p>
        <p>
            I have completed a <strong>Post Graduate Diploma in Computer Applications (PGDCA)</strong>,
            gaining one year of hands-on experience in computing and software fundamentals.
        </p>
    </section>

    <!-- PROFILE -->
    <section>
        <h2>My Profile</h2>
        <div class="cards">
            <div class="card">
                <h3>🎓 Student</h3>
                <p>Computer Science Engineering student with a strong technical foundation.</p>
            </div>
            <div class="card">
                <h3>💻 Developer</h3>
                <p>Creating modern websites using HTML & CSS with clean UI design.</p>
            </div>
            <div class="card">
                <h3>🎸 Musician</h3>
                <p>Guitar player with 1.5 years of experience. Music inspires creativity.</p>
            </div>
        </div>
    </section>

    <!-- SKILLS -->
    <section>
        <h2>Skills & Interests</h2>
        <ul>
            <li>HTML & CSS</li>
            <li>Programming & Problem Solving</li>
            <li>Web Development</li>
            <li>Guitar & Music</li>
        </ul>
    </section>

    <!-- CONTACT -->
    <section>
        <h2>Contact Me</h2>
        <ul>
            <li>📞 <a href="tel:+917637861188">+91 7637861188</a></li>
            <li>📧 <a href="mailto:ja3174257@gmail.com">ja3174257@gmail.com</a></li>
            <li>📍 Abhayapuri, Bongaigaon, Assam, India</li>
        </ul>
    </section>

    <!-- SOCIAL MEDIA -->
    <section>
        <h2>Connect With Me</h2>
        <div class="social-links">
            <a class="instagram" target="_blank"
               href="https://www.instagram.com/_creative_world_of_jahan?igsh=eTBkOTBycm96dDhw">
                <i class="fab fa-instagram"></i> Instagram
            </a>

            <a class="fbpage" target="_blank"
               href="https://www.facebook.com/share/1a368s9htQ/">
                <i class="fab fa-facebook"></i> Facebook Page
            </a>

            <a class="facebook" target="_blank"
               href="https://www.facebook.com/share/1D3cGi75KW/">
                <i class="fab fa-facebook-f"></i> Facebook
            </a>
        </div>
    </section>

</div>

<footer>
    <p>© 2026 Jahangir Alom | Personal Portfolio</p>
</footer>

</body>
</html>
