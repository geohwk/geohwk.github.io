<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>George Hawkins</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #001f26; /* darker monotone background */
      color: white;
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
    }

    header {
      text-align: center;
      padding: 60px 20px 30px;
    }

    .profile-pic {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid white;
      margin-bottom: 20px;
    }

    h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    h2 {
      margin-top: 10px;
      font-weight: 400;
    }

    nav {
      margin: 20px 0;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    nav a {
      margin: 6px 0;
      color: #80e5ff;
      text-decoration: none;
      font-size: 1.1rem;
    }

    nav a i {
      margin-right: 8px;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section.extras {
      background-color: transparent;
      padding: 40px 20px;
      width: 100%;
      text-align: center;
    }

    section.extras h3 {
      font-size: 1.8rem;
      margin-bottom: 20px;
    }

    section.extras ul {
      list-style: none;
      padding: 0;
    }

    section.extras li {
      margin: 10px 0;
      font-size: 1.1rem;
    }

    section.extras a {
      color: #80e5ff;
      text-decoration: none;
    }

    section.extras a i {
      margin-right: 8px;
    }

    section.extras a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <header>
    <img src="your-photo.jpg" alt="George Hawkins" class="profile-pic" />
    <h1>George Hawkins</h1>
    <h2>Software Engineer</h2>
    <nav>
      <a href="https://uk.linkedin.com/in/george-hawkins-637a7b9a" target="_blank">
        <i class="fab fa-linkedin"></i>LinkedIn
      </a>
      <a href="https://github.com/geohwk" target="_blank">
        <i class="fab fa-github"></i>GitHub
      </a>
    </nav>
  </header>

  <section class="extras">
    <h3>Extras</h3>
    <ul>
      <li><a href="https://www.youtube.com/@albiorix98" target="_blank"><i class="fab fa-youtube"></i>Stopmotion</a></li>
      <li><a href="https://rebrickable.com/users/albiorix/" target="_blank"><i class="fas fa-cubes"></i>Lego Instructions</a></li>
    </ul>
  </section>

</body>
</html>
