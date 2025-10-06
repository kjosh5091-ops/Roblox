# Roblox
Idk
fake-roblox-site/
├── index.html
├── style.css  (optional if separating CSS)
└── images/    (optional for any images you add)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Roblox (Totally Real)</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #232527;
      color: white;
      padding: 15px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .logo {
      font-size: 24px;
      font-weight: bold;
    }
    nav a {
      color: white;
      margin-left: 20px;
      text-decoration: none;
    }
    .hero {
      background-color: #d32f2f;
      color: white;
      padding: 100px 30px;
      text-align: center;
    }
    .hero h1 {
      font-size: 48px;
      margin-bottom: 20px;
    }
    .btn {
      background-color: #fff;
      color: #d32f2f;
      padding: 12px 25px;
      border: none;
      font-size: 16px;
      cursor: pointer;
      border-radius: 5px;
    }
    .games-section {
      padding: 40px 30px;
      text-align: center;
    }
    .games-grid {
      display: flex;
      justify-content: center;
      gap: 30px;
      flex-wrap: wrap;
    }
    .game-card {
      background-color: white;
      width: 200px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      overflow: hidden;
    }
    .game-card img {
      width: 100%;
      height: 120px;
      object-fit: cover;
    }
    .game-card p {
      padding: 10px;
      font-weight: bold;
    }
    footer {
      background-color: #232527;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 50px;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">ROBLOX*</div>
    <nav>
      <a href="#">Games</a>
      <a href="#">Avatar Shop</a>
      <a href="#">Create</a>
      <a href="#">Login</a>
      <a href="#">Sign Up</a>
    </nav>
  </header>

  <div class="hero">
    <h1>Imagine, Create, Play</h1>
    <p>Welcome to the most blocky world ever. Definitely real.</p>
    <button class="btn">Play Now</button>
  </div>

  <section class="games-section">
    <h2>Popular Games</h2>
    <div class="games-grid">
      <div class="game-card">
        <img src="https://via.placeholder.com/200x120?text=Obby+World" alt="Game 1"/>
        <p>Obby World</p>
      </div>
      <div class="game-card">
        <img src="https://via.placeholder.com/200x120?text=Tycoon+Madness" alt="Game 2"/>
        <p>Tycoon Madness</p>
      </div>
      <div class="game-card">
        <img src="https://via.placeholder.com/200x120?text=Sim+City" alt="Game 3"/>
        <p>Sim City</p>
      </div>
    </div>
  </section>

  <footer>
    <p>© 2025 Roblox Corporation (Not Really)</p>
  </footer>
</body>
</html>
from zipfile import ZipFile
import os

# Create project structure in memory
project_name = "fake-roblox-site"
html_content = '''<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Roblox (Totally Real)</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #232527;
      color: white;
      padding: 15px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .logo {
      font-size: 24px;
      font-weight: bold;
    }
    nav a {
      color: white;
      margin-left: 20px;
      text-decoration: none;
    }
    .hero {
      background-color: #d32f2f;
      color: white;
      padding: 100px 30px;
      text-align: center;
    }
    .hero h1 {
      font-size: 48px;
      margin-bottom: 20px;
    }
    .btn {
      background-color: #fff;
      color: #d32f2f;
      padding: 12px 25px;
      border: none;
      font-size: 16px;
      cursor: pointer;
      border-radius: 5px;
    }
    .games-section {
      padding: 40px 30px;
      text-align: center;
    }
    .games-grid {
      display: flex;
      justify-content: center;
      gap: 30px;
      flex-wrap: wrap;
    }
    .game-card {
      background-color: white;
      width: 200px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      overflow: hidden;
    }
    .game-card img {
      width: 100%;
      height: 120px;
      object-fit: cover;
    }
    .game-card p {
      padding: 10px;
      font-weight: bold;
    }
    footer {
      background-color: #232527;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 50px;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">ROBLOX*</div>
    <nav>
      <a href="#">Games</a>
      <a href="#">Avatar Shop</a>
      <a href="#">Create</a>
      <a href="#">Login</a>
      <a href="#">Sign Up</a>
    </nav>
  </header>

  <div class="hero">
    <h1>Imagine, Create, Play</h1>
    <p>Welcome to the most blocky world ever. Definitely real.</p>
    <button class="btn">Play Now</button>
  </div>

  <section class="games-section">
    <h2>Popular Games</h2>
    <div class="games-grid">
      <div class="game-card">
        <img src="https://via.placeholder.com/200x120?text=Obby+World" alt="Game 1"/>
        <p>Obby World</p>
      </div>
      <div class="game-card">
        <img src="https://via.placeholder.com/200x120?text=Tycoon+Madness" alt="Game 2"/>
        <p>Tycoon Madness</p>
      </div>
      <div class="game-card">
        <img src="https://via.placeholder.com/200x120?text=Sim+City" alt="Game 3"/>
        <p>Sim City</p>
      </div>
    </div>
  </section>

  <footer>
    <p>© 2025 Roblox Corporation (Not Really)</p>
  </footer>
</body>
</html>
'''

# Save HTML file and zip it
zip_filename = f"{project_name}.zip"
with ZipFile(zip_filename, 'w') as zipf:
    zipf.writestr("index.html", html_content)

zip_filename
