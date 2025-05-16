
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Adam Quatra - Personal Website</title>
  <link
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
    rel="stylesheet"
  />
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #121212;
      color: #f1c40f;
      margin: 0;
      padding: 20px;
      text-align: center;
    }

    h1 {
      font-size: 2.5em;
      margin-bottom: 0.2em;
      text-shadow: 0 0 8px #f1c40f;
    }

    .contact-info {
      margin-bottom: 20px;
    }

    .contact-info a {
      color: #f1c40f;
      text-decoration: none;
      margin: 0 12px;
      font-size: 1.1em;
      transition: color 0.3s ease;
    }

    .contact-info a:hover {
      color: #fff;
    }

    section {
      max-width: 600px;
      margin: 0 auto 40px;
      text-align: left;
      background: #222;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 15px #f1c40f;
    }

    section h2 {
      color: #f1c40f;
      text-align: center;
      margin-bottom: 15px;
      text-shadow: 0 0 6px #f1c40f;
    }

    section p {
      font-size: 1.1em;
      line-height: 1.6;
      color: #ddd;
    }

    .flag-container {
      text-align: center;
      margin-top: 15px;
    }

    .flag-container img {
      width: 150px;
      border-radius: 8px;
      box-shadow: 0 0 12px #f1c40f;
    }

    .slider {
      max-width: 500px;
      margin: 20px auto 0;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 0 15px #f1c40f;
      background: #222;
    }

    .slides {
      width: 100%;
      display: none;
      border-radius: 10px;
    }

    .slides.active {
      display: block;
    }

    .social-links {
      text-align: center;
      margin-top: 10px;
    }

    .social-links a {
      color: #f1c40f;
      margin: 0 10px;
      font-size: 1.8em;
      transition: color 0.3s ease;
      text-decoration: none;
    }

    .social-links a:hover {
      color: #fff;
    }

    .youtube-link {
      display: inline-block;
      margin-top: 10px;
      font-size: 1.2em;
      color: #f1c40f;
      text-decoration: none;
      transition: color 0.3s ease;
    }

    .youtube-link:hover {
      color: #fff;
    }

    footer {
      text-align: center;
      margin-top: 40px;
      color: #888;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <h1>Adam Quatra</h1>
  <div class="contact-info">
    <a href="mailto:katraadam2010@gmail.com"><i class="fas fa-envelope"></i> katraadam2010@gmail.com</a>
    <a href="https://www.youtube.com/channel/UCCBywHdsw2TgYCLhXNVHADA" target="_blank" rel="noopener noreferrer">
      <i class="fab fa-youtube"></i> My YouTube Channel
    </a>
  </div>

  <section>
    <h2>About Me</h2>
    <p>My name is <strong>Adam Quatra</strong>, I'm <strong>14 years old</strong>, and I live in <strong>Morocco</strong>. I'm a student who loves learning new things and exploring the world of technology.</p>
    
    <div class="flag-container">
      <img src="https://upload.wikimedia.org/wikipedia/commons/2/2c/Flag_of_Morocco.svg" alt="Flag of Morocco" />
    </div>
    
    <div class="slider">
      <img class="slides active" src="https://upload.wikimedia.org/wikipedia/commons/2/2c/Flag_of_Morocco.svg" alt="Flag of Morocco" />
      <img class="slides" src="https://images.unsplash.com/photo-1561510799-07bc2f0c302e?ixlib=rb-4.0.3&auto=format&fit=crop&w=900&q=80" alt="Jemaa el-Fnaa, Marrakech, Morocco" />
      <img class="slides" src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?ixlib=rb-4.0.3&auto=format&fit=crop&w=900&q=80" alt="Moroccan Desert" />
    </div>
  </section>

  <section>
    <h2>Hobbies</h2>
    <p>I enjoy programming, playing video games, creating websites, learning about space and science, and spending time with my friends. I also like watching tech videos and tutorials on YouTube.</p>
  </section>

  <section>
    <h2>Goals</h2>
    <p>My goal is to become a skilled developer or engineer in the future. I want to build apps,maybe games, and websites that help people and make life easier. I'm also interested in AI and robotics.</p>
  </section>

  <section>
    <h2>Contact Me</h2>
    <p>If you want to follow me or send me a message, here are my social media links:</p>
    <div class="social-links">
      <a href="#" title="Facebook"><i class="fab fa-facebook"></i></a>
      <a href="#" title="Instagram"><i class="fab fa-instagram"></i></a>
      <a href="#" title="TikTok"><i class="fab fa-tiktok"></i></a>
    </div>
  </section>
<!-- JavaScript for Auto Slide -->
  <section>
    <h2>My YouTube Channel</h2>
    <p>I also create and share content on YouTube. You can check out my channel here:</p>
    <a class="youtube-link" href="https://www.youtube.com/channel/UCCBywHdsw2TgYCLhXNVHADA" target="_blank" rel="noopener noreferrer">
      <i class="fab fa-youtube"></i> Visit my YouTube Channel
    </a>
  </section>
<script>
  let slideIndex = 0;
  const slides = document.querySelectorAll('.slides');

  function showSlides() {
    // hide all
    slides.forEach((slide) => (slide.classList.remove('active')));
    // show current
    slides[slideIndex].classList.add('active');
    // next index
    slideIndex = (slideIndex + 1) % slides.length;
    setTimeout(showSlides, 3000); // change every 3s
  }
  <footer>
    <p>© 2025 Adam Quatra. All rights reserved.</p>
  </footer>
</body>
</html>
