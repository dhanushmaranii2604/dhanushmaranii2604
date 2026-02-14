<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Dhanush M | Data Analyst Portfolio</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
:root{--bg:#f6f8fc;--card:#ffffff;--text:#1f2937;--accent:#2563eb}
.dark{--bg:#0f172a;--card:#111827;--text:#e5e7eb;--accent:#60a5fa}
*{box-sizing:border-box}
body{margin:0;font-family:Poppins,Arial;background:var(--bg);color:var(--text);transition:.3s}
nav{position:sticky;top:0;background:var(--card);padding:12px 20px;display:flex;justify-content:space-between;align-items:center;box-shadow:0 4px 10px rgba(0,0,0,.08)}
nav a{margin:0 10px;text-decoration:none;color:var(--text);font-weight:600}
.container{max-width:1100px;margin:auto;padding:20px}
.hero{text-align:center;padding:70px 20px}
.hero h1{font-size:40px;margin:0}
.typing{color:var(--accent);font-weight:600}
.btn{display:inline-block;margin-top:20px;background:var(--accent);color:#fff;padding:12px 20px;border-radius:8px;text-decoration:none;font-weight:600;transition:.25s}
.btn:hover{transform:translateY(-2px);box-shadow:0 10px 18px rgba(0,0,0,.15)}
.section{background:var(--card);margin-top:26px;padding:26px;border-radius:16px;box-shadow:0 8px 22px rgba(0,0,0,.06)}
.section h2{margin-top:0;border-bottom:2px solid rgba(0,0,0,.08);padding-bottom:10px}
.skills span{display:inline-block;background:rgba(37,99,235,.1);margin:6px;padding:8px 14px;border-radius:999px;font-size:14px}
.timeline{border-left:3px solid var(--accent);padding-left:20px}
.timeline div{margin-bottom:18px}
.project{margin-bottom:18px}
.project h3{margin-bottom:6px}
.chat{border:1px solid #ccc;border-radius:12px;padding:12px;margin-top:10px}
.chat input{width:70%;padding:8px}
.footer{text-align:center;margin-top:40px;opacity:.7}
.toggle{position:fixed;right:20px;top:20px;cursor:pointer;background:var(--card);padding:8px 12px;border-radius:20px;box-shadow:0 4px 10px rgba(0,0,0,.2)}
</style>
</head>
<body>
<div class="toggle" onclick="document.body.classList.toggle('dark')">🌙/☀️</div>
<nav>
<div><b>Dhanush M</b></div>
<div>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#education">Education</a>
<a href="#contact">Contact</a>
</div>
</nav>

<div class="container">

<div class="hero">
<h1>Hello 👋 I'm Dhanush</h1>
<p class="typing">Data Analyst | Python • SQL • Power BI • Excel</p>
<a class="btn" href="Dhanush_M_Resume.pdf" target="_blank">📄 Download Resume</a>
</div>

<div class="section" id="about">
<h2>🧠 About Me</h2>
<p>I am a passionate Data Analyst who enjoys turning raw datasets into meaningful business insights. I have worked on real datasets performing cleaning, preprocessing, visualization and reporting. My focus is on solving business problems through data-driven decisions rather than just coding models.</p>
<p><b>Currently Learning:</b> Advanced SQL, Window Functions, and Data Storytelling</p>
</div>

<div class="section" id="skills">
<h2>🛠 Technical Skills</h2>
<div class="skills">
<span>Python</span><span>SQL</span><span>Power BI</span><span>Excel</span><span>Tableau</span>
<span>Data Cleaning</span><span>EDA</span><span>Dashboarding</span><span>KPI Tracking</span><span>Trend Analysis</span>
</div>
<h3>⭐ Soft Skills</h3>
<p>Analytical Thinking • Problem Solving • Attention to Detail • Communication • Time Management</p>
</div>

<div class="section" id="projects">
<h2>🚀 Projects</h2>
<div class="project">
<h3>📈 Sales Forecasting & BI Dashboard</h3>
<p>Processed and analyzed 20,000+ sales records, built forecasting model and created dashboard to track KPIs and regional performance for business decision making.</p>
</div>
<div class="project">
<h3>🌿 AI Plant Disease Detection</h3>
<p>Performed exploratory data analysis and evaluated prediction results using image dataset and visualization techniques.</p>
</div>
</div>

<div class="section" id="education">
<h2>🎓 Education</h2>
<div class="timeline">
<div>
<b>MCA</b><br>
Nitte Meenakshi Institute of Technology — VTU (2023–2025)
</div>
<div>
<b>BCA</b><br>
Seshadripuram First Grade College — Bangalore City University (2020–2023)
</div>
</div>
</div>


<div class="section" id="contact">
<h2>📬 Contact</h2>
<p>Email: <a href="mailto:dhanushdhanu1941@gmail.com">dhanushdhanu1941@gmail.com</a></p>
<p>LinkedIn: <a href="https://linkedin.com/in/dhanush-thetechie" target="_blank">linkedin.com/in/dhanush-thetechie</a></p>
<p>GitHub: <a href="https://github.com/dhanushmaranii2604" target="_blank">github.com/dhanushmaranii2604</a></p>
</div>

<div class="footer">
<p>Thanks for visiting my profile 🙌</p>
<p><i>"Without data, you’re just another person with an opinion." </i></p>
<p>© 2026 Dhanush M</p>
</div>

</div>

<script>

function reply(){let q=document.getElementById('q').value.toLowerCase();let ans="Try asking about skills or projects";if(q.includes('skill'))ans="Python, SQL, Power BI, Excel, Tableau";if(q.includes('project'))ans="Sales Forecasting Dashboard and AI Plant Disease Detection";document.getElementById('a').innerText=ans}
</script>
</body>
</html>
