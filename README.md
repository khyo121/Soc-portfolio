
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Khari Owens | SOC Analyst Portfolio</title>
<style>
/* General Styling */
body { 
  font-family: Arial, sans-serif; 
  margin: 0; 
  padding: 0; 
  background: linear-gradient(135deg, #0f2027, #203a43, #2c5364); 
  color: #eaeaea;
}

/* Container */
.container { 
  max-width: 1000px; 
  margin: 0 auto; 
  padding: 30px; 
  color: #333;
}

/* Hero Section */
.hero {
  background: url('images/cyber-bg.jpg') center/cover no-repeat;
  text-align: center;
  color: #fff;
  padding: 120px 20px;
}
.hero h1 {
  font-size: 3em;
  margin-bottom: 10px;
  text-shadow: 2px 2px 10px rgba(0,0,0,0.7);
}
.hero p {
  font-size: 1.2em;
  max-width: 700px;
  margin: auto;
  text-shadow: 1px 1px 6px rgba(0,0,0,0.6);
}

/* Section Headings */
h2 { 
  color: #1b4d89; 
  margin-top: 50px; 
  border-left: 5px solid #1b4d89; 
  padding-left: 10px; 
}

/* Links */
a { 
  color: #1b4d89; 
  text-decoration: none; 
  font-weight: bold;
}
a:hover { 
  color: #0f2027; 
  text-decoration: underline; 
}

/* Sections */
.section {
  margin-bottom: 60px; 
}

/* Video Embeds */
iframe.video-frame { 
  width: 100%; 
  max-width: 800px; 
  height: 450px; 
  border: 3px solid #1b4d89; 
  border-radius: 8px; 
  box-shadow: 0 4px 12px rgba(0,0,0,0.3);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}
iframe.video-frame:hover {
  transform: scale(1.02);
  box-shadow: 0 6px 16px rgba(0,0,0,0.35);
}

/* Certifications Badge */
.certifications .badge {
  height: 80px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.25);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  vertical-align: middle;
  margin-right: 15px;
}
.certifications .badge:hover {
  transform: scale(1.05);
  box-shadow: 0 6px 16px rgba(0,0,0,0.35);
}

/* Tools / Skills */
.tools {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
  justify-content: center;
}
.tools img {
  width: 80px;
  height: 80px;
  object-fit: contain;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.25);
  transition: transform 0.2s ease;
}
.tools img:hover {
  transform: scale(1.1);
}

/* Contact */
.contact {
  text-align: center;
  padding: 40px 20px;
  background: rgba(255,255,255,0.1);
  border-radius: 12px;
}
.contact a {
  margin: 0 10px;
  color: #fff;
  font-size: 1.2em;
}
</style>
</head>
<body>

<!-- Hero Section -->
<div class="hero">
  <h1>Khari Owens</h1>
  <p>SOC Analyst | Cybersecurity Enthusiast | Showcasing Threat Investigations, Reports, and Certifications</p>
</div>

<div class="container">

  <!-- First Updated Video -->
  <div class="section">
    <h2>Static Analysis in Reverse Engineering: A Deep Dive</h2>
    <iframe class="video-frame" src="https://player.vimeo.com/video/1114762484" allowfullscreen></iframe>
  </div>

  <!-- Second Video -->
  <div class="section">
    <h2>🖥️ Event Log Threat Analysis</h2>
    <iframe class="video-frame" src="https://www.youtube.com/embed/YOUR_VIDEO_ID" allowfullscreen></iframe>
  </div>

  <!-- Incident Reports -->
  <div class="section">
    <h2>📄 Incident Reports</h2>
    <ul>
      <li><a href="reports/phishing.pdf" target="_blank">Phishing Case Report (PDF)</a></li>
      <li><a href="reports/malware.pdf" target="_blank">Malware Alert Report (PDF)</a></li>
    </ul>
  </div>

  <!-- Certifications -->
  <div class="section">
    <h2>🎓 Certifications</h2>
    <div class="certifications">
      <a href="https://www.credly.com/badges/d1b72ac2-c77c-4a11-8078-8c2e9c4aa1bd/public_url" target="_blank">
        <img src="images/comptia-a-ce-certification.1.png" alt="CompTIA A+ CE Badge" class="badge">
      </a>
      <a href="https://www.credly.com/badges/d9fd4974-bd10-4554-9040-a5659d27fb7d/public_url" target="_blank">
        <img src="images/comptia-security-ce-certification.png" alt="CompTIA Security+ CE Badge" class="badge">
      </a>
    </div>
    <ul>
      <li>CompTIA Network+</li>
      <li>CompTIA CySA+ (in progress)</li>
      <li>CompTIA Project+</li>
      <li>SecurityX</li>
    </ul>
  </div>

  <!-- Tools / Skills -->
  <div class="section">
    <h2>🛠️ Tools & Skills</h2>
    <div class="tools">
      <img src="images/Splunk-Logo.jpg" alt="Splunk">
      <img src="images/wire shark.webp" alt="Wireshark">
      <img src="images/elk.png" alt="ELK Stack">
      <img src="images/python.png" alt="Python">
      <img src="images/osint.png" alt="OSINT Tools">
    </div>
  </div>

  <!-- Contact -->
  <div class="section contact">
    <h2>📬 Contact Me</h2>
    <p>Connect or reach out:</p>
    <a href="mailto:your.email@example.com">Email</a>
    <a href="https://www.linkedin.com/in/khariowens" target="_blank">LinkedIn</a>
    <a href="https://github.com/khyo121" target="_blank">GitHub</a>
  </div>

</div>
</body>
</html>
