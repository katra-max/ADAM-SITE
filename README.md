
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<meta name="description" content="Personal website of Adam Quatra, a young tech enthusiast from Morocco who loves programming, gaming, and creating YouTube content." />
<meta name="keywords" content="Adam Quatra, programming, gaming, Morocco, YouTube channel, developer, technology, coding, goals, contact" />
<meta name="author" content="Adam Quatra" />
<meta name="robots" content="index, follow" />
<title>Adam Quatra - Personal Website</title>
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet" />
<style>
  body {
    font-family: Arial, sans-serif;
    background-color: #121212;
    color: #f1c40f;
    margin: 0;
    padding: 20px;
    padding-top: 60px;
    text-align: center;
    scroll-behavior: smooth;
  }
  nav {
    position: fixed;
    top: 0; left: 0; right: 0;
    background: #222;
    box-shadow: 0 2px 5px rgba(0,0,0,0.7);
    z-index: 100;
  }
  .navbar {
    display: flex;
    justify-content: center;
    list-style: none;
    margin: 0; padding: 10px 0;
  }
  .navbar li {
    margin: 0 15px;
  }
  .navbar a {
    color: #f1c40f;
    text-decoration: none;
    font-weight: 600;
    transition: color 0.3s;
    cursor: pointer;
  }
  .navbar a:hover {
    color: #fff;
  }
  section {
    max-width: 700px;
    margin: 40px auto;
    background: #222;
    padding: 25px;
    border-radius: 12px;
    box-shadow: 0 0 15px #f1c40f;
    text-align: center;
  }
  section h1 {
    margin-bottom: 5px;
    font-size: 2.2em;
    color: #f1c40f;
    text-shadow: 0 0 8px #f1c40f;
  }
  section h2 {
    margin-top: 0;
    margin-bottom: 20px;
    font-size: 1.5em;
    color: #f39c12;
    font-weight: 400;
    font-style: italic;
  }
  section p, section img, section h2 {
    display: none;
  }
  section.active p,
  section.active img,
  section.active h2,
  section.active .social-links {
    display: block;
  }
  section img {
    width: 100%;
    max-height: 280px;
    margin-top: 20px;
    border: 4px solid #f1c40f;
    border-radius: 15px;
    object-fit: cover;
    box-shadow: 0 0 25px #f39c12;
  }
  .social-links {
    margin-top: 15px;
  }
  .social-links a {
    color: #f1c40f;
    margin: 0 15px;
    font-size: 2em;
    transition: color 0.3s ease;
    text-decoration: none;
    filter: drop-shadow(0 0 3px #f1c40f);
  }
  .social-links a:hover {
    color: #fff;
    filter: drop-shadow(0 0 8px #f39c12);
  }
  footer {
    text-align: center;
    margin-top: 50px;
    color: #888;
    font-size: 0.9em;
  }
  @media (max-width: 650px) {
    section {
      margin: 30px 15px;
    }
    section h1 {
      font-size: 1.8em;
    }
    section h2 {
      font-size: 1.2em;
    }
    .social-links a {
      font-size: 1.5em;
      margin: 0 10px;
    }
  }
</style>
</head>
<body>
  <nav>
    <ul class="navbar">
      <li><a data-target="about">About Me</a></li>
      <li><a data-target="hobbies">Hobbies</a></li>
      <li><a data-target="goals">Goals</a></li>
      <li><a data-target="youtube">YouTube Channel</a></li>
      <li><a data-target="contact">Contact Me</a></li>
    </ul>
  </nav>

  <section id="about" class="active">
    <h1>About Me</h1>
    <h2>Get to know Adam Quatra</h2>
    <p>My name is <strong>Adam Quatra</strong>, I'm <strong>14 years old</strong>, and I live in <strong>Morocco</strong>. I'm a student who loves learning new things and exploring the world of technology.</p>
    <img src="https://upload.wikimedia.org/wikipedia/commons/2/2c/Flag_of_Morocco.svg" alt="Flag of Morocco" />
  </section>

  <section id="hobbies">
    <h1>Hobbies</h1>
    <h2>What I love to do</h2>
    <p>I enjoy programming, playing video games, creating websites, learning about space and science, and spending time with my friends. I also like watching tech videos and tutorials on YouTube.</p>
    <img src="https://cdn-icons-png.flaticon.com/512/1006/1006553.png" alt="Programming and Gaming Icon" />
  </section>

  <section id="goals">
    <h1>Goals</h1>
    <h2>My ambitions</h2>
    <p>My goal is to become a skilled developer or engineer in the future. I want to build apps, maybe games, and websites that help people and make life easier. I'm also interested in AI and robotics.</p>
    <img src="https://cdn-icons-png.flaticon.com/512/3448/3448615.png" alt="Goals Icon" style="width: 100%; max-height: 350px; margin-top: 20px; border: 4px solid #f1c40f; border-radius: 15px; object-fit: contain; box-shadow: 0 0 30px #f39c12;" />
  </section>

  <section id="youtube">
  <h1>YouTube Channel</h1>
  <h2>Check out my content</h2>
  <p>I also create and share content on YouTube. You can check out my channel here:</p>
  <div class="social-links">
    <a href="https://www.youtube.com/channel/UCCBywHdsw2TgYCLhXNVHADA" target="_blank" rel="noopener noreferrer" title="YouTube"><i class="fab fa-youtube"></i></a>
  </div>
  <img src="https://upload.wikimedia.org/wikipedia/commons/7/75/YouTube_social_white_squircle_%282017%29.svg" alt="YouTube Logo" />
</section>
  <section id="contact">
    <h1>Contact Me</h1>
    <h2>Get in touch</h2>
    <p>If you want to follow me or send me a message, here are my social media links:</p>
    <div class="social-links">
      <a href="mailto:katraadam2010@gmail.com" title="Email"><i class="fas fa-envelope"></i></a>
      <a href="https://discordapp.com/users/adamquatra2010" target="_blank" rel="noopener noreferrer" title="Discord"><i class="fab fa-discord"></i></a>
    </div>
    <img src="https://images.unsplash.com/photo-1504384308090-c894fdcc538d?auto=format&fit=crop&w=700&q=80" alt="Contact" />
  </section>

  <footer>
    &copy; 2025 Adam Quatra - All Rights Reserved
  </footer>

<script>
  const navLinks = document.querySelectorAll('nav a');
  const sections = document.querySelectorAll('section');

  navLinks.forEach(link => {
    link.addEventListener('click', () => {
      const targetId = link.getAttribute('data-target');

      sections.forEach(section => {
        if(section.id === targetId){
          section.classList.add('active');
          section.scrollIntoView({behavior: 'smooth'});
        } else {
          section.classList.remove('active');
        }
      });
    });
  });
</script>
</body>
</html>
