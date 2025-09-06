<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Papri Bhattacharjee - GitHub Profile</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: #f8f8f8;
            line-height: 1.6;
            padding: 20px;
            min-height: 100vh;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            text-align: center;
            margin-bottom: 30px;
            padding: 20px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 20px;
            backdrop-filter: blur(10px);
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.2);
        }
        
        .scenery-container {
            margin: 20px auto;
            width: 700px;
            height: 200px;
            overflow: hidden;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.4);
        }
        
        .scenery-container img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        h1 {
            font-size: 2.8rem;
            margin: 15px 0;
            color: #ff79c6;
            text-shadow: 0 0 10px rgba(255, 121, 198, 0.5);
        }
        
        .tagline {
            font-size: 1.4rem;
            color: #bd93f9;
            margin-bottom: 10px;
        }
        
        .typing-container {
            height: 60px;
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 20px 0;
        }
        
        .typing-text {
            font-size: 1.8rem;
            font-weight: bold;
            color: #8be9fd;
            text-align: center;
            min-height: 60px;
            display: flex;
            align-items: center;
        }
        
        .about-section {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            margin-bottom: 40px;
        }
        
        .card {
            flex: 1;
            min-width: 300px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 20px;
            padding: 25px;
            backdrop-filter: blur(10px);
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.2);
        }
        
        .card h2 {
            color: #50fa7b;
            margin-bottom: 20px;
            font-size: 1.8rem;
            border-bottom: 2px solid #50fa7b;
            padding-bottom: 10px;
        }
        
        .tech-stack {
            text-align: center;
            margin-bottom: 40px;
        }
        
        .tech-icons {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 25px;
            margin: 20px 0;
        }
        
        .tech-icon {
            width: 70px;
            height: 70px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            padding: 10px;
            transition: transform 0.3s, background 0.3s;
        }
        
        .tech-icon:hover {
            transform: translateY(-5px);
            background: rgba(255, 255, 255, 0.2);
        }
        
        .tech-icon i {
            font-size: 2rem;
            margin-bottom: 5px;
        }
        
        .stats-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
            margin-bottom: 40px;
        }
        
        .stat-box {
            width: 280px;
            height: 165px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            padding: 15px;
            backdrop-filter: blur(10px);
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s;
        }
        
        .stat-box:hover {
            transform: scale(1.03);
        }
        
        .connect-section {
            text-align: center;
            margin-bottom: 40px;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
        
        .social-btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            background: rgba(255, 255, 255, 0.1);
            color: white;
            text-decoration: none;
            padding: 12px 25px;
            border-radius: 50px;
            font-weight: bold;
            transition: all 0.3s;
            backdrop-filter: blur(10px);
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.2);
        }
        
        .social-btn:hover {
            background: rgba(255, 255, 255, 0.2);
            transform: translateY(-3px);
        }
        
        .social-btn i {
            margin-right: 8px;
        }
        
        .github-btn {
            background: linear-gradient(45deg, #6e5494, #8a63d2);
        }
        
        .linkedin-btn {
            background: linear-gradient(45deg, #0077b5, #00a0dc);
        }
        
        .email-btn {
            background: linear-gradient(45deg, #d44638, #ea4335);
        }
        
        footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px;
            color: #bd93f9;
            font-size: 0.9rem;
        }
        
        @media (max-width: 768px) {
            .scenery-container {
                width: 100%;
                height: 180px;
            }
            
            h1 {
                font-size: 2.2rem;
            }
            
            .tagline {
                font-size: 1.2rem;
            }
            
            .typing-text {
                font-size: 1.4rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>👋 Hi, I'm Papri Bhattacharjee</h1>
            <p class="tagline">💻 Java Developer | 🛠 IoT Enthusiast</p>
            <p class="tagline">🎓 B.Tech in Electronics & Communication (Techno Main Salt Lake, 2022–2026)</p>
            
            <!-- Animated Scenery Banner -->
            <div class="scenery-container">
                <img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExdzhsMGQwb3JxeDR2YmE2b3RlNnp0cnMwYjk2eWp2Y2kxczB0aDE1NSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/p9YXZMSnQzkwx7w4Mo/giphy.gif" alt="Animated Scenery">
            </div>
            
            <!-- Typing Animation -->
            <div class="typing-container">
                <div class="typing-text" id="typing-text"></div>
            </div>
        </header>
        
        <section class="about-section">
            <div class="card">
                <h2>🚀 About Me</h2>
                <p>Motivated <strong>Electronics & Communication</strong> undergraduate with strong skills in <strong>Java</strong>, <strong>SQL</strong>, <strong>IoT systems</strong>, and <strong>Web Development</strong>.</p>
                <p>Passionate about building impactful applications — from <strong>banking software</strong> to <strong>IoT monitoring systems</strong>.</p>
                <p>Problem-solving mindset with a focus on clean, modular code.</p>
            </div>
            
            <div class="card">
                <h2>📚 Education</h2>
                <p><strong>B.Tech in Electronics & Communication Engineering</strong></p>
                <p>Techno Main Salt Lake, Kolkata</p>
                <p>2022 – 2026</p>
                <p>Currently pursuing my undergraduate degree with a focus on IoT systems and embedded programming.</p>
            </div>
        </section>
        
        <section class="tech-stack">
            <h2>🛠 Tech Stack</h2>
            <div class="tech-icons">
                <div class="tech-icon">
                    <i class="fab fa-java"></i>
                    <span>Java</span>
                </div>
                <div class="tech-icon">
                    <i class="fas fa-database"></i>
                    <span>MySQL</span>
                </div>
                <div class="tech-icon">
                    <i class="fab fa-cuttlefish"></i>
                    <span>C</span>
                </div>
                <div class="tech-icon">
                    <i class="fab fa-cplusplus"></i>
                    <span>C++</span>
                </div>
                <div class="tech-icon">
                    <i class="fab fa-html5"></i>
                    <span>HTML5</span>
                </div>
                <div class="tech-icon">
                    <i class="fab fa-css3-alt"></i>
                    <span>CSS3</span>
                </div>
                <div class="tech-icon">
                    <i class="fab fa-js-square"></i>
                    <span>JavaScript</span>
                </div>
            </div>
        </section>
        
        <section class="stats-container">
            <div class="stat-box">
                <h2>📊 GitHub Stats</h2>
                <p>Check out my coding activity and contributions on GitHub.</p>
                <p>Passionate about open source and collaborative projects.</p>
            </div>
            
            <div class="stat-box">
                <h2>🌱 Currently Learning</h2>
                <p>Advanced Java frameworks</p>
                <p>IoT security protocols</p>
                <p>Cloud computing basics</p>
            </div>
            
            <div class="stat-box">
                <h2>🎯 Goals for 2024</h2>
                <p>Contribute to open source projects</p>
                <p>Develop a complete IoT solution</p>
                <p>Master data structures & algorithms</p>
            </div>
        </section>
        
        <section class="connect-section">
            <h2>📫 Connect With Me</h2>
            <div class="social-links">
                <a href="https://github.com/papri221003" class="social-btn github-btn">
                    <i class="fab fa-github"></i> GitHub
                </a>
                <a href="https://www.linkedin.com/in/papri-bhattacharjee-5a1311251" class="social-btn linkedin-btn">
                    <i class="fab fa-linkedin"></i> LinkedIn
                </a>
                <a href="mailto:bhpapri03@gmail.com" class="social-btn email-btn">
                    <i class="fas fa-envelope"></i> Email
                </a>
            </div>
        </section>
        
        <footer>
            <p>Made with ❤️ by Papri Bhattacharjee | &copy; 2023</p>
        </footer>
    </div>

    <script>
        // Typing animation effect
        const texts = [
            "Java Developer",
            "IoT Enthusiast",
            "Electronics & Communication Undergrad",
            "Passionate Problem Solver"
        ];
        
        let textIndex = 0;
        let charIndex = 0;
        let isDeleting = false;
        let typingDelay = 100;
        let erasingDelay = 50;
        let newTextDelay = 2000;
        
        function type() {
            const currentText = texts[textIndex];
            const typingElement = document.getElementById("typing-text");
            
            if (isDeleting) {
                // Remove characters
                typingElement.textContent = currentText.substring(0, charIndex - 1);
                charIndex--;
                typingDelay = erasingDelay;
            } else {
                // Add characters
                typingElement.textContent = currentText.substring(0, charIndex + 1);
                charIndex++;
                typingDelay = 100;
            }
            
            // Check if complete
            if (!isDeleting && charIndex === currentText.length) {
                isDeleting = true;
                typingDelay = newTextDelay;
            } else if (isDeleting && charIndex === 0) {
                isDeleting = false;
                textIndex = (textIndex + 1) % texts.length;
                typingDelay = 500;
            }
            
            setTimeout(type, typingDelay);
        }
        
        // Start the typing effect when page loads
        window.onload = function() {
            setTimeout(type, newTextDelay + 250);
        };
    </script>
</body>
</html>
