<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dagmawi Ayenew - Portfolio</title>
  <style>
    body {
      font-family: 'Fira Code', monospace;
      background-color: #1A1B27;
      color: #FFFFFF;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
    }
    /* New Header Design */
    .header {
      text-align: center;
      padding: 40px 0;
      background: linear-gradient(135deg, #FF6B6B, #4ECDC4, #45B7D1);
      border-radius: 10px;
      position: relative;
      overflow: hidden;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
    }
    .header::before {
      content: '';
      position: absolute;
      top: 0;
      left: -100%;
      width: 100%;
      height: 100%;
      background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.2), transparent);
      animation: shine 3s infinite;
    }
    @keyframes shine {
      0% { left: -100%; }
      50% { left: 100%; }
      100% { left: 100%; }
    }
    .header h1 {
      font-size: 36px;
      margin: 0;
      color: #FFFFFF;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
    }
    .header p {
      font-size: 16px;
      color: #FFFFFF;
      margin: 10px 0 0;
    }
    h2, h3 {
      color: #FF6B6B;
      text-align: center;
    }
    p, table {
      color: #FFFFFF;
    }
    .section {
      margin: 40px 0;
    }
    .social-links a {
      margin: 0 10px;
      display: inline-block;
    }
    .tech-stack table {
      width: 100%;
      border-collapse: collapse;
      margin: 20px 0;
    }
    .tech-stack td {
      text-align: center;
      padding: 10px;
    }
    .tech-stack span {
      font-size: 14px;
    }
    .projects table, .overview table {
      width: 100%;
      border-collapse: collapse;
      margin: 20px 0;
    }
    .projects td, .overview td {
      padding: 15px;
      vertical-align: top;
      width: 50%;
    }
    .mermaid-diagram {
      text-align: center;
      background: #2E2E2E;
      padding: 20px;
      border-radius: 10px;
    }
    .additional-tools {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
    }
    .additional-tools div {
      margin: 10px;
    }
    .center {
      text-align: center;
    }
    img {
      max-width: 100%;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- New Header -->
    <div class="header">
      <h1>Dagmawi Ayenew</h1>
      <p>Computer Engineering Student | AI Enthusiast | Full-Stack Developer</p>
    </div>

    <!-- Typing Animation -->
    <h3 class="center">
      <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=4ECDC4¢er=true&vCenter=true&width=600&lines=Transforming+Ideas+into+Intelligent+Solutions" alt="Typing SVG" />
    </h3>

    <!-- About Me -->
    <div class="section">
      <h2>About Me</h2>
      <p class="center">Computer Engineering student passionate about building innovative solutions through AI, full-stack development, and data engineering. Dedicated to creating scalable, efficient, and impactful technology for tomorrow.</p>
      <div class="social-links center">
        <a href="https://linkedin.com/in/dagmawi-ayenew" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
        <a href="https://twitter.com/dagiayy" target="_blank"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter" /></a>
        <a href="https://dagmawi.vercel.app" target="_blank"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=FFEAA7" alt="Portfolio" /></a>
        <a href="mailto:dagmawi@example.com" target="_blank"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
      </div>
    </div>

    <!-- Professional Overview -->
    <div class="section">
      <h2>Professional Overview</h2>
      <table class="overview">
        <tr>
          <td>
            <h3>Academic Background</h3>
            <ul>
              <li><strong>Computer Engineering Student</strong> with a focus on AI/ML</li>
              <li><strong>Research Interests</strong>: Artificial Intelligence, IoT Systems, Data Engineering</li>
              <li><strong>Key Projects</strong>: Advanced algorithms, system design, machine learning models</li>
            </ul>
          </td>
          <td>
            <h3>Professional Expertise</h3>
            <ul>
              <li><strong>Full-Stack Development</strong> (Web & Mobile)</li>
              <li><strong>AI/ML Implementation</strong> & Model Deployment</li>
              <li><strong>Database Architecture</strong> & Optimization</li>
            </ul>
          </td>
        </tr>
      </table>
    </div>

    <!-- Tech Stack -->
    <div class="section tech-stack">
      <h2>Tech Stack</h2>
      <table>
        <tr>
          <td><img src="https://techstack-generator.vercel.app/react-icon.svg" alt="React" width="40" height="40" /><br><span style="color:#FF6B6B">React</span></td>
          <td><img src="https://techstack-generator.vercel.app/python-icon.svg" alt="Python" width="40" height="40" /><br><span style="color:#4ECDC4">Python</span></td>
          <td><img src="https://techstack-generator.vercel.app/js-icon.svg" alt="JavaScript" width="40" height="40" /><br><span style="color:#FFEAA7">JavaScript</span></td>
          <td><img src="https://techstack-generator.vercel.app/cpp-icon.svg" alt="C++" width="40" height="40" /><br><span style="color:#45B7D1">C++</span></td>
          <td><img src="https://techstack-generator.vercel.app/django-icon.svg" alt="Django" width="40" height="40" /><br><span style="color:#96CEB4">Django</span></td>
          <td><img src="https://skillicons.dev/icons?i=nodejs" alt="Node.js" width="40" height="40" /><br><span style="color:#FF6B6B">Node.js</span></td>
          <td><img src="https://skillicons.dev/icons?i=mongodb" alt="MongoDB" width="40" height="40" /><br><span style="color:#4ECDC4">MongoDB</span></td>
          <td><img src="https://skillicons.dev/icons?i=postgres" alt="PostgreSQL" width="40" height="40" /><br><span style="color:#FFEAA7">PostgreSQL</span></td>
        </tr>
        <tr>
          <td><img src="https://skillicons.dev/icons?i=typescript" alt="TypeScript" width="40" height="40" /><br><span style="color:#45B7D1">TypeScript</span></td>
          <td><img src="https://techstack-generator.vercel.app/aws-icon.svg" alt="AWS" width="40" height="40" /><br><span style="color:#96CEB4">AWS</span></td>
          <td><img src="https://skillicons.dev/icons?i=flutter" alt="Flutter" width="40" height="40" /><br><span style="color:#FF6B6B">Flutter</span></td>
          <td><img src="https://skillicons.dev/icons?i=tensorflow" alt="TensorFlow" width="40" height="40" /><br><span style="color:#4ECDC4">TensorFlow</span></td>
          <td><img src="https://skillicons.dev/icons?i=pytorch" alt="PyTorch" width="40" height="40" /><br><span style="color:#FFEAA7">PyTorch</span></td>
          <td><img src="https://skillicons.dev/icons?i=redis" alt="Redis" width="40" height="40" /><br><span style="color:#45B7D1">Redis</span></td>
          <td><img src="https://skillicons.dev/icons?i=git" alt="Git" width="40" height="40" /><br><span style="color:#96CEB4">Git</span></td>
          <td><img src="https://skillicons.dev/icons?i=vscode" alt="VS Code" width="40" height="40" /><br><span style="color:#FF6B6B">VS Code</span></td>
        </tr>
      </table>
    </div>

    <!-- Featured Projects -->
    <div class="section projects">
      <h2>Featured Projects</h2>
      <table>
        <tr>
          <td>
            <h3>AI Study Assistance Platform</h3>
            <p><strong>Tech Stack</strong>: Python, TensorFlow, React, Node.js, MongoDB</p>
            <p><strong>Description</strong>: An intelligent tutoring system offering personalized learning paths, performance analytics, and adaptive questioning algorithms.</p>
            <p><strong>Impact</strong>: Improved learning outcomes by 60%.</p>
          </td>
          <td>
            <h3>Enterprise Link Management Suite</h3>
            <p><strong>Tech Stack</strong>: React, Django, PostgreSQL, AWS</p>
            <p><strong>Description</strong>: A multi-tenant platform with advanced analytics, enterprise-grade security, and an API-first design.</p>
            <p><strong>Impact</strong>: Reduced content management time by 45%.</p>
          </td>
        </tr>
      </table>
    </div>

    <!-- Performance Metrics -->
    <div class="section">
      <h2>Performance Metrics</h2>
      <p class="center">
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=Dagiayy&theme=dracula&hide_border=true&background=1A1B27&stroke=4ECDC4&ring=4ECDC4&fire=FF6B6B&currStreakLabel=4ECDC4" alt="Contribution Streak" width="45%" />
      </p>
      <p class="center">
        <img src="https://github-readme-activity-graph.vercel.app/graph?username=Dagiayy&theme=dracula&hide_border=true&bg_color=1A1B27&color=FFEAA7&line=45B7D1&point=96CEB4&area=true&custom_title=Development%20Activity%20Timeline" alt="Activity Graph" width="90%" />
      </p>
      <p class="center">
        <img src="https://github-profile-trophy.vercel.app/?username=Dagiayy&theme=dracula&column=-1&layout=compact" alt="GitHub Trophies" width="90%" />
      </p>
    </div>

    <!-- Professional Development -->
    <div class="section">
      <h2>Professional Development</h2>
      <div class="mermaid-diagram">
        <script type="module">
          import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
          mermaid.initialize({ startOnLoad: true });
        </script>
        <div class="mermaid">
          graph LR
            A[Computer Engineering] --> B[Full-Stack Development]
            B --> C[AI/ML Specialization]
            C --> D[Data Engineering]
            D --> E[Enterprise Solutions]
            style A fill:#FF6B6B,stroke:#FFFFFF,stroke-width:2px,color:#FFFFFF
            style B fill:#4ECDC4,stroke:#FFFFFF,stroke-width:2px,color:#FFFFFF
            style C fill:#45B7D1,stroke:#FFFFFF,stroke-width:2px,color:#FFFFFF
            style D fill:#96CEB4,stroke:#FFFFFF,stroke-width:2px,color:#FFFFFF
            style E fill:#FFEAA7,stroke:#FFFFFF,stroke-width:2px,color:#1A1B27
        </div>
      </div>
    </div>

    <!-- Additional Tools -->
    <div class="section">
      <h2>Additional Tools</h2>
      <div class="additional-tools">
        <div><img src="https://img.shields.io/badge/-Figma-F24E1E?style=flat-square&logo=figma&logoColor=white" alt="Figma" /></div>
        <div><img src="https://img.shields.io/badge/-Canva-00C4B4?style=flat-square&logo=canva&logoColor=white" alt="Canva" /></div>
        <div><img src="https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel&logoColor=FFEAA7" alt="Vercel" /></div>
        <div><img src="https://img.shields.io/badge/-AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white" alt="AWS" /></div>
        <div><img src="https://img.shields.io/badge/-Heroku-430098?style=flat-square&logo=heroku&logoColor=white" alt="Heroku" /></div>
        <div><img src="https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" /></div>
      </div>
    </div>

    <!-- Visitor Counter -->
    <div class="section center">
      <h2>Visitor Count</h2>
      <img src="https://profile-counter.glitch.me/Dagiayy/count.svg" alt="Visitor Counter" />
    </div>

    <!-- Footer -->
    <div class="section center">
      <img src="https://github.com/jrohitofficial/jrohitofficial/blob/master/thankyou%20RJ.svg" alt="Thanks for Visiting" width="90%" />
    </div>
  </div>
</body>
</html>
