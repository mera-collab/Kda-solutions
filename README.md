# Kda-solutions
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KDA Student Achievements</title>
<style>
  /* --- Global Styles --- */
  body {
    margin: 0;
    font-family: 'Segoe UI', Arial, sans-serif;
    background-color: #f9fafc;
    color: #333;
  }

  header {
    background: #004aad;
    color: white;
    padding: 20px 0;
    text-align: center;
  }

  header h1 {
    margin: 0;
  }

  nav {
    background: #023e8a;
    padding: 10px;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
  }

  nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
  }

  nav a:hover {
    text-decoration: underline;
  }

  section {
    padding: 40px 20px;
    max-width: 1000px;
    margin: auto;
  }

  h2 {
    color: #004aad;
    border-bottom: 3px solid #004aad;
    display: inline-block;
    padding-bottom: 5px;
  }

  /* --- Achievement Cards --- */
  .achievements {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
  }

  .card {
    background: white;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    border-radius: 10px;
    width: 280px;
    padding: 15px;
    text-align: center;
    transition: transform 0.2s;
  }

  .card:hover {
    transform: scale(1.03);
  }

  .card img {
    width: 100%;
    height: 180px;
    border-radius: 8px;
    object-fit: cover;
  }

  .card h3 {
    color: #023e8a;
    margin: 10px 0 5px 0;
  }

  .card p {
    font-size: 14px;
    color: #555;
  }

  /* --- Gallery --- */
  .gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 15px;
  }

  .gallery img {
    width: 100%;
    border-radius: 8px;
  }

  /* --- News --- */
  .news-item {
    background: white;
    padding: 15px;
    border-left: 5px solid #004aad;
    margin-bottom: 15px;
  }

  /* --- Search & Admin --- */
  .search-bar {
    margin: 20px 0;
    text-align: center;
  }

  .search-bar input {
    width: 60%;
    padding: 10px;
    font-size: 16px;
    border: 2px solid #004aad;
    border-radius: 8px;
  }

  .admin {
    background: #e0e7ff;
    padding: 20px;
    border-radius: 10px;
    text-align: center;
  }

  footer {
    background: #004aad;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 40px;
  }

</style>
</head>
<body>

<header>
  <h1>KDA Student Achievements</h1>
  <p>Celebrating Excellence in Academics, Sports, Arts, and Leadership</p>
</header>

<nav>
  <a href="#achievements">Achievements</a>
  <a href="#students">Students</a>
  <a href="#gallery">Gallery</a>
  <a href="#news">News</a>
  <a href="#admin">Admin</a>
</nav>

<!-- Search -->
<section id="search">
  <div class="search-bar">
    <input type="text" id="searchInput" placeholder="Search achievements by name or category...">
  </div>
</section>

<!-- Achievements Section -->
<section id="achievements">
  <h2>🏆 Achievements</h2>
  <div class="achievements" id="achievementList">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1521737604893-d14cc237f11d?auto=format&fit=crop&w=800&q=80" alt="Science Fair">
      <h3>Science Fair Winner</h3>
      <p><b>Student:</b> Aisha Khan</p>
      <p><b>Category:</b> Academics</p>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1517649763962-0c623066013b?auto=format&fit=crop&w=800&q=80" alt="Sports">
      <h3>National Sprint Champion</h3>
      <p><b>Student:</b> Ahmed Malik</p>
      <p><b>Category:</b> Sports</p>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1520974722228-3d77c37f5f74?auto=format&fit=crop&w=800&q=80" alt="Art Award">
      <h3>Best Painting Award</h3>
      <p><b>Student:</b> Zara Ali</p>
      <p><b>Category:</b> Arts</p>
    </div>
  </div>
</section>

<!-- Student Profiles -->
<section id="students">
  <h2>👩‍🎓 Student Profiles</h2>
  <p>Meet our outstanding students making KDA proud.</p>
  <ul>
    <li><b>Aisha Khan:</b> Science enthusiast and top scorer in national fair.</li>
    <li><b>Ahmed Malik:</b> Passionate athlete representing KDA at national level.</li>
    <li><b>Zara Ali:</b> Talented painter with multiple art competition wins.</li>
  </ul>
</section>

<!-- Gallery -->
<section id="gallery">
  <h2>🖼️ Photo & Video Gallery</h2>
  <div class="gallery">
    <img src="https://images.unsplash.com/photo-1529333166437-7750a6dd5a70?auto=format&fit=crop&w=800&q=80" alt="Event 1">
    <img src="https://images.unsplash.com/photo-1503676260728-1c00da094a0b?auto=format&fit=crop&w=800&q=80" alt="Event 2">
    <img src="https://images.unsplash.com/photo-1532634726-8b9fb99825c7?auto=format&fit=crop&w=800&q=80" alt="Event 3">
  </div>
</section>

<!-- News & Updates -->
<section id="news">
  <h2>📰 News & Updates</h2>
  <div class="news-item">
    <h3>Annual Achievement Day Announced</h3>
    <p>The school will host the Annual Achievement Day on December 12 to honor outstanding students.</p>
  </div>
  <div class="news-item">
    <h3>KDA Students Shine in Citywide Science Expo</h3>
    <p>Four students from KDA bagged top positions in the Karachi Science Expo 2025.</p>
  </div>
</section>

<!-- Admin Panel (Demo) -->
<section id="admin">
  <h2>🔑 Admin Panel (Demo)</h2>
  <div class="admin">
    <p>Upload new achievements (For future dynamic setup)</p>
    <form>
      <input type="text" placeholder="Student Name" required><br><br>
      <input type="text" placeholder="Achievement Title" required><br><br>
      <input type="file" accept="image/*"><br><br>
      <button type="button">Upload</button>
    </form>
  </div>
</section>

<footer>
  <p>© 2025 KDA School | Designed to Celebrate Our Students</p>
</footer>

<script>
  // --- Simple Search Filter Function ---
  const searchInput = document.getElementById('searchInput');
  const cards = document.querySelectorAll('.card');

  searchInput.addEventListener('keyup', function() {
    const query = this.value.toLowerCase();
    cards.forEach(card => {
      const text = card.innerText.toLowerCase();
      card.style.display = text.includes(query) ? '' : 'none';
    });
  });
</script>

</body>
</html>
