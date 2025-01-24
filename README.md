<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" integrity="sha512-9usAa10IRO0HhonpyAIVpjrylPvoDwiPUiKdWk5t3PyolY1cOd4DSE0Ga+ri4AuTroPR5aQvXU9xC6qOPnzFeg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>

    <header>
        <nav>
            <div class="logo">Your Name</div>
            <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="hero">
           <div class="hero-content">
            <h1>Hello, I'm Your Name</h1>
             <p>A brief description of your skills and passions.</p>
             <a href="#portfolio" class="btn">View My Work</a>
           </div>
           <div class="hero-img">
             <img src="images/hero.png" alt="Your image">
           </div>
        </section>

        <section id="about" class="container">
            <h2>About Me</h2>
            <div class="about-content">
              <img src="images/profile.jpg" alt="Your Profile Picture" class="profile-pic">
              <div class="text-content">
                 <p>A more detailed paragraph about yourself, your background, and interests. You can talk about your skills and goals here.</p>
                 <p>You can expand on your experience and what you have accomplished</p>
                 <div class="social-icons">
                    <a href="#" target="_blank"><i class="fab fa-github"></i></a>
                    <a href="#" target="_blank"><i class="fab fa-linkedin"></i></a>
                    <a href="#" target="_blank"><i class="fab fa-twitter"></i></a>
                    <!-- Add more social icons as needed -->
                </div>
              </div>
            </div>
          </section>

        <section id="portfolio" class="container">
            <h2>Portfolio</h2>
            <div class="portfolio-grid">
              <div class="portfolio-item">
                <img src="images/project1.jpg" alt="Project 1">
                <h3>Project Title 1</h3>
                <p>Short description of project 1.</p>
                <a href="#" class="btn">View Project</a>
              </div>
              <div class="portfolio-item">
                <img src="images/project2.jpg" alt="Project 2">
                <h3>Project Title 2</h3>
                <p>Short description of project 2.</p>
                <a href="#" class="btn">View Project</a>
              </div>
               <div class="portfolio-item">
                <img src="images/project3.jpg" alt="Project 3">
                <h3>Project Title 3</h3>
                <p>Short description of project 3.</p>
                <a href="#" class="btn">View Project</a>
              </div>
            <!-- Add more portfolio items as needed -->
            </div>
        </section>

        <section id="contact" class="container">
            <h2>Contact Me</h2>
            <div class="contact-content">
                <p>Feel free to reach out with questions or collaboration ideas!</p>
                 <form action="#" method="post" class="contact-form">
                    <div class="form-group">
                        <label for="name">Name</label>
                        <input type="text" id="name" name="name" required>
                    </div>
                    <div class="form-group">
                        <label for="email">Email</label>
                         <input type="email" id="email" name="email" required>
                     </div>
                     <div class="form-group">
                        <label for="message">Message</label>
                        <textarea id="message" name="message" required></textarea>
                    </div>
                    <button type="submit" class="btn">Send Message</button>
                 </form>
            </div>
        </section>
    </main>

    <footer>
        <p>© 2023 Your Name. All rights reserved.</p>
    </footer>

</body>
</html>
