<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Yehia Ibrahim Saleh</title>
  <style>
    /* Reset & Base */
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f9f9f9;
      color: #333;
      scroll-behavior: smooth;
    }

    h1, h3, p {
      margin: 0;
      padding: 0.5em 0;
    }

    a {
      text-decoration: none;
    }

    /* Animations */
    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(40px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes slideIn {
      from {
        opacity: 0;
        transform: translateX(-40px);
      }
      to {
        opacity: 1;
        transform: translateX(0);
      }
    }

    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }

    @keyframes blink {
      50% { border-color: transparent; }
    }

    .fade-in {
      animation: fadeInUp 1s ease forwards;
      opacity: 0;
    }

    .fade-in-delayed {
      animation: fadeInUp 1.5s ease forwards;
      opacity: 0;
    }

    .typing-effect {
      display: inline-block;
      white-space: nowrap;
      overflow: hidden;
      border-right: 2px solid #0077B5;
      animation: typing 4s steps(40, end), blink 0.75s step-end infinite;
      width: 0;
    }

    .badge-container img {
      margin: 0.3em;
      transition: transform 0.3s ease;
    }

    .badge-container img:hover {
      transform: scale(1.05);
    }

    .section {
      max-width: 900px;
      margin: auto;
      padding: 2em;
    }

    .center {
      text-align: center;
    }

    .highlight {
      color: #0077B5;
      font-weight: bold;
    }

    .contact-icons img {
      margin: 0.5em;
      transition: transform 0.3s ease;
    }

    .contact-icons img:hover {
      transform: scale(1.1);
    }
  </style>
</head>
<body>

  <section class="section center fade-in">
    <h1>🚀 <span class="highlight">Yehia Ibrahim Saleh</span></h1>
    <h3 class="fade-in-delayed">Full Stack Developer | IT Specialist | Cybersecurity Enthusiast</h3>
    <p class="typing-effect">Building. Securing. Innovating.</p>

    <div class="badge-container">
      <img src="https://img.shields.io/badge/Full%20Stack%20Developer-%230077B5.svg?style=flat&logo=react&logoColor=white"/>
      <img src="https://img.shields.io/badge/IT%20Support-%23F7DF1E.svg?style=flat&logo=linux&logoColor=black"/>
      <img src="https://img.shields.io/badge/Cybersecurity-%231572B6.svg?style=flat&logo=security&logoColor=white"/>
    </div>
  </section>

  <section class="section fade-in-delayed">
    <h2>🔍 About Me</h2>
    <p>
      I’m <strong>Yehia Ibrahim</strong>, a <span class="highlight">Full Stack Developer</span> and <span class="highlight">IT Specialist</span> with a BSc in Computer Science and a dual degree from Egypt and the UK.
    </p>
    <p>
      I specialize in:
      <ul>
        <li>⚙️ Scalable Web Applications</li>
        <li>🔧 System Administration</li>
        <li>🔐 Cybersecurity & Threat Mitigation</li>
        <li>📡 IT Support & Networking</li>
      </ul>
    </p>
    <p>
      My mission: <strong>Deliver real-world digital solutions</strong> and help businesses thrive securely in a connected world.
    </p>
  </section>

  <section class="section fade-in">
    <h2>🏅 Certifications</h2>
    <ul>
      <li>🎓 Google IT Support, IT Security, System Admin, Cisco Networking</li>
      <li>🔐 Cyber Attack Countermeasures, Real-Time Threat Detection</li>
      <li>💻 IBM Data Science, HackerRank Problem Solving & Python</li>
    </ul>
  </section>

  <section class="section fade-in-delayed">
    <h2>🧰 Tech Stack</h2>
    <p><strong>Languages & Frameworks:</strong> JavaScript, React, Node.js, Python, Java</p>
    <p><strong>Security:</strong> Linux, Network Security, AWS, Cryptography</p>
    <p><strong>IT Support:</strong> System Admin, DNS, Active Directory, Troubleshooting</p>
  </section>

  <section class="section fade-in">
    <h2>🚀 Projects</h2>
    <ul>
      <li><strong>HeyDoc:</strong> AI chatbot for medical support.</li>
      <li><strong>Computer Guardian:</strong> Cyber threat monitoring system.</li>
      <li><strong>SIC-XE Assembler:</strong> Python-based architecture simulator.</li>
      <li><strong>Portfolio Website:</strong> Fully responsive React + Tailwind site.</li>
    </ul>
  </section>

  <section class="section center fade-in-delayed">
    <h2>📬 Contact Me</h2>
    <div class="contact-icons">
      <a href="mailto:yahyaibrahem45@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white"/></a>
      <a href="https://www.linkedin.com/in/yehia-ibrahim-8154b0201/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white"/></a>
      <a href="https://wa.me/+971564269560" target="_blank"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=flat&logo=whatsapp&logoColor=white"/></a>
    </div>
  </section>

  <section class="section center fade-in">
    <h3>✨ Let’s innovate, secure, and build the future together ✨</h3>
  </section>

</body>
</html>
