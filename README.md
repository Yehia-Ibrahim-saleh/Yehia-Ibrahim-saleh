<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animated README Preview</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            background: #0d1117;
            color: #c9d1d9;
            padding: 20px;
            margin: 0;
            line-height: 1.6;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: #161b22;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 8px 32px rgba(0,0,0,0.3);
        }

        h1 {
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 10px;
            background: linear-gradient(45deg, #00ff88, #0077ff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .rocket {
            display: inline-block;
            animation: rocket-float 3s ease-in-out infinite;
        }

        .fade-in {
            animation: fadeIn 2s ease-in-out;
        }

        .subtitle {
            text-align: center;
            font-size: 1.2em;
            margin-bottom: 20px;
            color: #7c3aed;
        }

        .typing {
            display: inline-block;
            white-space: nowrap;
            overflow: hidden;
            border-right: 2px solid #00ff88;
            animation: typing 3.5s steps(40, end), blink .75s step-end infinite;
            font-weight: bold;
            color: #00ff88;
        }

        .badges {
            text-align: center;
            margin: 20px 0;
        }

        .badges img {
            margin: 5px;
            transition: transform 0.3s ease;
        }

        .badges img:hover {
            transform: scale(1.1);
            animation: badge-glow 1s ease-in-out;
        }

        .section-title {
            font-size: 1.5em;
            margin: 30px 0 15px 0;
            background: linear-gradient(45deg, #ff6b6b, #4ecdc4);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            animation: slideInLeft 1s ease-out;
        }

        .about-content {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
            animation: slideInUp 1s ease-out;
        }

        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 15px;
            margin: 20px 0;
        }

        .tech-item {
            background: #21262d;
            padding: 15px;
            border-radius: 8px;
            text-align: center;
            transition: all 0.3s ease;
            border: 1px solid #30363d;
            animation: fadeInUp 0.8s ease-out;
        }

        .tech-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,255,136,0.2);
            border-color: #00ff88;
        }

        .project-card {
            background: #21262d;
            padding: 20px;
            margin: 15px 0;
            border-radius: 10px;
            border-left: 4px solid #7c3aed;
            transition: all 0.3s ease;
            animation: slideInRight 1s ease-out;
        }

        .project-card:hover {
            transform: translateX(10px);
            box-shadow: 0 5px 20px rgba(124, 58, 237, 0.3);
        }

        .contact-section {
            text-align: center;
            margin: 30px 0;
        }

        .contact-section a {
            display: inline-block;
            margin: 10px;
            transition: transform 0.3s ease;
        }

        .contact-section a:hover {
            transform: scale(1.1) rotate(5deg);
        }

        .footer {
            text-align: center;
            font-size: 1.1em;
            margin-top: 40px;
            animation: pulse 2s ease-in-out infinite;
        }

        /* Animations */
        @keyframes fadeIn {
            0% { opacity: 0; transform: translateY(-20px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        @keyframes fadeInUp {
            0% { opacity: 0; transform: translateY(30px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        @keyframes slideInLeft {
            0% { opacity: 0; transform: translateX(-50px); }
            100% { opacity: 1; transform: translateX(0); }
        }

        @keyframes slideInRight {
            0% { opacity: 0; transform: translateX(50px); }
            100% { opacity: 1; transform: translateX(0); }
        }

        @keyframes slideInUp {
            0% { opacity: 0; transform: translateY(30px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        @keyframes typing {
            from { width: 0; }
            to { width: 100%; }
        }

        @keyframes blink {
            50% { border-color: transparent; }
        }

        @keyframes rocket-float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }

        @keyframes badge-glow {
            0%, 100% { box-shadow: 0 0 5px rgba(0,255,136,0.3); }
            50% { box-shadow: 0 0 20px rgba(0,255,136,0.8); }
        }

        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.7; }
        }

        hr {
            border: none;
            height: 2px;
            background: linear-gradient(90deg, transparent, #00ff88, transparent);
            margin: 30px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1><span class="rocket">🚀</span> <span class="fade-in">Yehia Ibrahim Saleh</span></h1>
        <h3 class="subtitle">Full Stack Developer | IT Specialist | Cybersecurity Enthusiast</h3>
        
        <div class="badges">
            <img src="https://img.shields.io/badge/Full%20Stack%20Developer-%230077B5.svg?style=flat&logo=react&logoColor=white"/>
            <img src="https://img.shields.io/badge/IT%20Support-%23F7DF1E.svg?style=flat&logo=linux&logoColor=black"/>
            <img src="https://img.shields.io/badge/Cybersecurity-%231572B6.svg?style=flat&logo=security&logoColor=white"/>
        </div>

        <hr>

        <h2 class="section-title">🔍 <span class="fade-in">About Me</span></h2>
        <div class="about-content">
            <p>👋 I'm <strong>Yehia Ibrahim</strong>, a <strong>results-oriented Full Stack Developer</strong> and <strong>IT Specialist</strong> with a background in Computer Science and a dual degree from Egypt 🇪🇬 and the UK 🇬🇧.</p>
            
            <p><strong>I specialize in:</strong></p>
            <ul>
                <li>Building scalable applications ⚙️</li>
                <li>Providing robust IT support 🛠️</li>
                <li>Enhancing cybersecurity 🔐</li>
            </ul>
            
            <p>🚀 <span class="typing">Always learning. Always building. Always securing.</span></p>
        </div>

        <hr>

        <h2 class="section-title">🏅 Certifications</h2>
        <div class="tech-grid">
            <div class="tech-item">
                <h4>🎓 IT & System Administration</h4>
                <p>• Google IT Support<br>
                • System Admin & Infrastructure<br>
                • Cisco Networks<br>
                • IT Security Fundamentals</p>
            </div>
            <div class="tech-item">
                <h4>🔐 Cybersecurity</h4>
                <p>• Intro to Cybersecurity<br>
                • Cyber Attack Countermeasures<br>
                • Threat Detection & Mitigation</p>
            </div>
            <div class="tech-item">
                <h4>💻 Development & Data</h4>
                <p>• IBM Data Scientist<br>
                • HackerRank Problem Solving<br>
                • HackerRank Python</p>
            </div>
        </div>

        <hr>

        <h2 class="section-title">🧰 Tech Stack</h2>
        <div class="about-content">
            <p><strong>Languages & Frameworks:</strong><br>
            🟨 JavaScript & React | 🟦 Python & Django | 🟧 Java | 🟩 Node.js</p>
            
            <p><strong>Security & IT:</strong><br>
            🐧 Linux | 🔐 Network Security | ☁️ AWS | 🧾 Cryptography<br>
            🖥️ System Admin | 🌐 DNS | 🧩 Troubleshooting | 🪪 Active Directory</p>
        </div>

        <hr>

        <h2 class="section-title">🚀 Projects</h2>
        
        <div class="project-card">
            <h3>🩺 HeyDoc Chatbot</h3>
            <p>AI assistant for healthcare-related queries & triage.</p>
        </div>

        <div class="project-card">
            <h3>🔐 Computer Guardian</h3>
            <p>A real-time security monitoring platform.</p>
        </div>

        <div class="project-card">
            <h3>⚙️ SIC-XE Assembler</h3>
            <p>Low-level instruction assembler built in Python.</p>
        </div>

        <div class="project-card">
            <h3>🌐 Portfolio Website</h3>
            <p>Responsive React + Tailwind portfolio to showcase work.</p>
        </div>

        <hr>

        <h2 class="section-title">📬 Contact Me</h2>
        <div class="contact-section">
            <a href="mailto:yahyaibrahem45@gmail.com">
                <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white"/>
            </a>
            <a href="https://www.linkedin.com/in/yehia-ibrahim-8154b0201/">
                <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white"/>
            </a>
            <a href="https://wa.me/+971564269560">
                <img src="https://img.shields.io/badge/WhatsApp-25D366?style=flat&logo=whatsapp&logoColor=white"/>
            </a>
        </div>

        <hr>

        <div class="footer">
            <h3>✨ Let's innovate, secure, and build the future together. ✨</h3>
        </div>
    </div>
</body>
</html>
