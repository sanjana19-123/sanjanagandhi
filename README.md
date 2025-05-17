<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sanjana Gandhi | QA Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      font-family: 'Inter', sans-serif;
      background: linear-gradient(to bottom right, #eef2f3, #8e9eab);
      margin: 0;
      padding: 0;
      color: #1f2937;
    }
    header {
      background: linear-gradient(120deg, #4f46e5, #6366f1);
      color: white;
      padding: 3rem 1rem;
      text-align: center;
      border-bottom: 5px solid #3b82f6;
    }
    header h1 {
      margin: 0;
      font-size: 3rem;
    }
    header p {
      margin: 1rem 0 0;
      font-weight: 300;
      font-size: 1.2rem;
    }
    .container {
      max-width: 960px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    .card {
      background: white;
      border-radius: 16px;
      padding: 2rem;
      margin-bottom: 2rem;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    .card h2 {
      margin-top: 0;
      color: #1e3a8a;
    }
    .btn {
      background-color: #2563eb;
      color: white;
      padding: 0.6rem 1.2rem;
      border-radius: 8px;
      text-decoration: none;
      font-weight: 600;
      display: inline-block;
      margin-top: 1rem;
      transition: background-color 0.3s ease;
    }
    .btn:hover {
      background-color: #1d4ed8;
    }
    .profile-img {
      width: 140px;
      height: 140px;
      object-fit: cover;
      border-radius: 50%;
      border: 4px solid #ffffff;
      margin-bottom: 1rem;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }
    .center {
      text-align: center;
    }
    ul li {
      margin-bottom: 0.5rem;
    }
    a {
      color: #1d4ed8;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <img class="profile-img" src="https://avatars.githubusercontent.com/u/00000000?v=4" alt="Profile Photo">
    <h1>Sanjana Gandhi</h1>
    <p>QA Automation Engineer | Selenium, API, ETL, Cloud Testing | Toronto 🇨🇦</p>
  </header>

  <div class="container">
    <div class="card center">
      <h2>📄 Resume</h2>
      <a class="btn" href="./Sanjana_Gandhi_Resume.pdf" download>Download Resume</a>
    </div>

    <div class="card">
      <h2>🚀 Featured Projects</h2>
      <ul>
        <li><strong>Selenium UI Automation</strong>: <a href="https://github.com/yourusername/selenium-ui-automation">Automates login and checkout for SauceDemo</a></li>
        <li><strong>API Testing with Karate</strong>: <a href="https://github.com/yourusername/api-testing-karate">REST API testing using Karate DSL with BDD</a></li>
        <li><strong>ETL Testing Pipeline</strong>: <a href="https://github.com/yourusername/etl-testing-pipeline">Data validation and pipeline testing with SQL + Python</a></li>
      </ul>
    </div>

    <div class="card">
      <h2>🔧 Skills Snapshot</h2>
      <p><strong>Languages:</strong> Java, Python, SQL</p>
      <p><strong>Tools:</strong> Selenium, REST Assured, Karate, Jenkins, Docker, Git, Postman</p>
      <p><strong>Platforms:</strong> AWS, GCP (BigQuery, Dataflow)</p>
      <p><strong>Frameworks:</strong> TestNG, PyTest, Cucumber, BDD/TDD</p>
    </div>

    <div class="card">
      <h2>📫 Contact</h2>
      <p><strong>Email:</strong> <a href="mailto:gsanjanasanju0932@gmail.com">gsanjanasanju0932@gmail.com</a></p>
      <p><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/sanjana-gandhi-123842289/">Sanjana Gandhi</a></p>
      <p><strong>Location:</strong> Toronto, Ontario, Canada</p>
    </div>
  </div>
</body>
</html>
