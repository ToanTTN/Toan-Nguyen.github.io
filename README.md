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
Use code with caution.
Html
CSS (style.css):
/* General Styles */
body {
  font-family: 'Roboto', sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
  color: #333;
  background-color: #f8f8f8;
}

a {
    text-decoration: none;
    color: #007bff;
}

a:hover{
    color: #0056b3;
}

.container {
  width: 80%;
  max-width: 1200px;
  margin: 0 auto;
  padding: 40px 0;
}

h1, h2, h3 {
  margin-bottom: 15px;
  color: #222;
}

.btn {
  display: inline-block;
  padding: 10px 20px;
  background-color: #007bff;
  color: #fff;
  border: none;
  border-radius: 5px;
  text-decoration: none;
  cursor: pointer;
  transition: background-color 0.3s;
}

.btn:hover {
  background-color: #0056b3;
}

/* Header Styles */
header {
  background-color: #fff;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  position: sticky;
  top: 0;
  z-index: 100;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 0;
  width: 80%;
  max-width: 1200px;
  margin: 0 auto;
}

.logo {
  font-size: 1.5em;
  font-weight: bold;
  color: #222;
}

.nav-links {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  gap: 25px;
}

.nav-links li a {
  color: #222;
  transition: color 0.3s;
}

.nav-links li a:hover {
  color: #007bff;
}

/* Hero Section */
#hero {
    background-color: #e9ecef;
    padding: 80px 0;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: left;
}

.hero-content{
  width: 50%;
  padding-right: 40px;
}

#hero h1 {
  font-size: 2.5em;
  margin-bottom: 15px;
}

#hero p{
  font-size: 1.1em;
  margin-bottom: 25px;
  color: #555;
}

.hero-img{
  width: 40%;
  text-align: center;
}

.hero-img img{
    max-width: 100%;
    height: auto;
    border-radius: 10px;
}

/* About Section */
#about{
  text-align: center;
}
.about-content{
  display: flex;
  align-items: center;
  gap: 50px;
  margin-top: 30px;
}

.profile-pic{
    max-width: 300px;
    border-radius: 50%;
    height: auto;
}

.text-content{
  text-align: left;
}

.social-icons{
  margin-top: 20px;
}
.social-icons a {
  font-size: 25px;
  margin-right: 10px;
  color: #333;
}
.social-icons a:hover {
    color: #007bff;
}

/* Portfolio Section */
.portfolio-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
  margin-top: 30px;
}

.portfolio-item {
  background-color: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  text-align: center;
}

.portfolio-item img {
  max-width: 100%;
  height: auto;
  border-radius: 5px;
  margin-bottom: 15px;
}

/* Contact Section */
#contact{
    text-align: center;
}

.contact-content{
  margin-top: 30px;
}

.contact-form{
   margin: 0 auto;
   width: 70%;
   max-width: 600px;
   text-align: left;
   margin-top: 20px;
}

.form-group {
    margin-bottom: 20px;
}

.form-group label {
    display: block;
    margin-bottom: 5px;
}

.form-group input,
.form-group textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 4px;
}

.form-group textarea {
  height: 150px;
}

/* Footer */
footer {
  text-align: center;
  padding: 20px 0;
  background-color: #333;
  color: #fff;
}

/* Responsive design */
@media (max-width: 768px) {
  .container {
    width: 90%;
  }

  nav {
    flex-direction: column;
    align-items: flex-start;
  }

  .nav-links{
    margin-top: 15px;
    flex-direction: column;
    align-items: flex-start;
    gap: 10px;
  }

  #hero{
    flex-direction: column;
  }
  .hero-content, .hero-img {
    width: 90%;
    padding-right: 0;
  }

  .about-content{
    flex-direction: column;
    gap: 20px;
  }

    .profile-pic{
      max-width: 80%;
  }
}
