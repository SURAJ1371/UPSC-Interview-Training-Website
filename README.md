# UPSC-Interview-Training-Website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UPSC Mock Interview Training</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #0073e6;
            color: white;
            text-align: center;
            padding: 40px 0;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #575757;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }
        .content-section {
            background: white;
            padding: 20px;
            margin-bottom: 30px;
            border-radius: 8px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
        }
        .content-section h2 {
            color: #0073e6;
            margin-bottom: 10px;
        }
        .content-section p {
            line-height: 1.7;
        }
        .content-section .video {
            text-align: center;
            margin-top: 20px;
        }
        .content-section .video iframe {
            width: 100%;
            height: 400px;
            border: none;
            border-radius: 8px;
        }
        .testimonial-section {
            background-color: #e8f0fe;
            padding: 40px 20px;
            margin-bottom: 30px;
            text-align: center;
        }
        .testimonial-section h2 {
            color: #0073e6;
        }
        .testimonial {
            display: inline-block;
            margin: 20px;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            max-width: 300px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
        }
        .contact-form input,
        .contact-form textarea {
            padding: 10px;
            margin-bottom: 15px;
            border-radius: 5px;
            border: 1px solid #ccc;
            font-size: 16px;
            width: 100%;
        }
        .contact-form button {
            background-color: #0073e6;
            color: white;
            border: none;
            padding: 12px;
            font-size: 18px;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #005bb5;
        }
    </style>
</head>
<body>
    <header>
        <h1>UPSC Mock Interview Training</h1>
        <p>Prepare for your UPSC interview with top experts</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About Us</a>
        <a href="#courses">Courses</a>
        <a href="#testimonials">Testimonials</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <section id="home" class="content-section">
            <h2>Welcome to UPSC Mock Interview Training</h2>
            <p>Our program is designed to simulate real UPSC interviews, offering detailed feedback and personalized guidance. Learn from top interviewers and refine your skills to ace the final stage of the exam.</p>
            <div class="video">
                <h3>Watch a Sample Mock Interview</h3>
                <iframe src="https://www.youtube.com/embed/examplevideo" allowfullscreen></iframe>
            </div>
        </section>

        <section id="about" class="content-section">
            <h2>About Us</h2>
            <p>We are a team of UPSC mentors and former interview board members. With years of experience, we have successfully helped thousands of candidates excel in the interview process.</p>
        </section>

        <section id="courses" class="content-section">
            <h2>Our Courses</h2>
            <p>Choose from a range of courses, including full mock interviews, personalized feedback sessions, and interview strategy workshops.</p>
        </section>

        <section id="testimonials" class="testimonial-section">
            <h2>What Our Students Say</h2>
            <div class="testimonial">
                <p>"The mock interview process was extremely close to the real one. The feedback helped me correct my mistakes and gain confidence." - Candidate A</p>
            </div>
            <div class="testimonial">
                <p>"The guidance I received here was invaluable. I was able to approach the interview with clarity and calmness." - Candidate B</p>
            </div>
            <div class="testimonial">
                <p>"The expert panel's insights into my performance truly prepared me for the actual interview." - Candidate C</p>
            </div>
        </section>

        <section id="contact" class="content-section">
            <h2>Contact Us</h2>
            <form class="contact-form">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
                <button type="submit">Submit</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 UPSC Mock Interview Training. All Rights Reserved.</p>
    </footer>
</body>
</html>
