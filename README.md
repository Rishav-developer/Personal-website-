<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rishav Kr. | Student</title>
    <style>
          /* Reset and Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(120deg, #dce6ff, #b8c7ff);
            color: #333;
            line-height: 1.6;
            scroll-behavior: smooth;
        }

        /* Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        @keyframes typing {
            from {
                width: 0;
            }
            to {
                width: 100%;
            }
        }
        @keyframes blink {
            50% {
                border-color: transparent;
            }
        }

        /* Header Section */
        header {
            background-color: #344CB7;
            color: white;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        header h4 {
            font-size: 20px;
            font-weight: bold;
            letter-spacing: 1px;
        }

        /* Navigation Section */
        nav {
            position: sticky;
            top: 0;
            background: white;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
            z-index: 1000;
        }
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            padding: 15px 0;
        }
        nav a {
            text-decoration: none;
            color: #344CB7;
            margin: 0 15px;
            font-size: 16px;
            font-weight: bold;
            text-transform: uppercase;
            transition: color 0.3s, transform 0.3s;
        }
        nav a:hover {
            color: #1d2f7b;
            transform: scale(1.1);
        }

        /* Hero Section */
        .hero {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 50px 20px;
            flex-wrap: wrap;
            background: white;
            margin: 20px auto;
            max-width: 1200px;
            border-radius: 15px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            animation: fadeInUp 1s ease-out;
        }
        .hero-text {
            max-width: 600px;
            text-align: left;
        }
        .hero-text h2 {
            font-size: 40px;
            margin-bottom: 10px;
            color: #333;
            white-space: nowrap;
            border-right: 2px solid #333;
            animation: typing 3s steps(20, end), blink 0.5s step-end infinite alternate;
            overflow: hidden;
        }
        .hero-text span {
            color: #344CB7;
            font-weight: bold;
        }
        .hero-text p {
            font-size: 18px;
            margin: 15px 0;
            color: #666;
        }
        .hero-text .btn {
            display: inline-block;
            padding: 12px 25px;
            margin-top: 15px;
            background: #344CB7;
            color: white;
            text-decoration: none;
            border-radius: 25px;
            transition: all 0.3s;
            font-size: 16px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        .hero-text .btn:hover {
            background: #1d2f7b;
        }

        /* Skills Section */
        .skills {
            padding: 50px 20px;
            text-align: center;
            background: #f1f4ff;
        }
        .skills h2 {
            font-size: 28px;
            margin-bottom: 30px;
            color: #344CB7;
        }
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .skill-card {
            background: white;
            width: 250px;
            padding: 20px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .skill-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
        }

 /* Contact and Sign-Up Section */
        .form-sections {
            display: flex;
            justify-content: center;
            align-items: flex-start;
            gap: 20px;
            padding: 50px 20px;
            background: #f9f9f9;
            flex-wrap: wrap; /* Makes it responsive */
        }
        .form-container {
            background: #ffffff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 100%;
            max-width: 450px; /* Sets a maximum width */
            text-align: center;
        }
        .form-container h2 {
            color: var(--primary-color);
            margin-bottom: 15px;
        }
        .form-container form {
            display: flex;
            flex-direction: column;
        }
        .form-container input, .form-container textarea {
            margin: 10px 0;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 16px;
        }
        .form-container button {
            padding: 10px 20px;
            background: #344CB7;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s;
        }
        .form-container button:hover {
            background: #e60000;
        }
        
        /* Footer Section */
        footer {
            background: #344CB7;
            color: white;
            text-align: center;
            padding: 20px;
        }
        footer p {
            font-size: 14px;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h4>TrueTrail Innovation</h4>
    </header>

    <!-- Navigation Section -->
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#skills">Protofolio</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><a href="#gallery">Gallery</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="hero-text">
            <h2>Hello</h2>
            <h2>I am <span>Rishav Kr.</span></h2>
            <p>I am a student in class 8 at Saraswati Vidya Mandir. And the owner of <b>TrueTrail Innovation </b></p>
            <a href="#contact" class="btn">Contact Me</a>
        </div>
    </section>

    <!-- Skills Section -->
    <section class="skills" id="skills">
        <h2>My Skills</h2>
        <div class="skills-container">
            <div class="skill-card">
                <h3>Web Development</h3>
                <p>HTML, CSS, and JavaScript basics</p>
            </div>
            <div class="skill-card">
                <h3>Hobbies</h3>
                <p>Coding, solving puzzles, and exploring technology</p>
            </div>
        </div>
    </section>
      <!-- Contact and Sign-Up Section -->
    <section class="form-sections">
        <!-- Contact Form -->
        <div class="form-container">
            <h2>Contact Me</h2>
            <form>
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" rows="5" required></textarea>
                <button type="submit">Send</button>
            </form>
        </div>
        <!-- Sign-Up Form -->
        <div class="form-container">
            <h2>Sign Up</h2>
            <form>
                <input type="text" placeholder="Username" required>
                <input type="email" placeholder="Email" required>
                <input type="password" placeholder="Password" required>
                <button type="submit">Sign Up</button>
            </form>
        </div>
    </section>
    

    <!-- Footer Section -->
    <footer>
        <p>© 2025 Rishav Kr. | Designed by <b>TrueTrail Innovation</b>.
        <br> TrueTrail Innovation is owned by <b>Rishav kumar</b></p>
        <hr color="white"size="3"align="center" width="100%">
    </footer>
</body>
</html>