<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Personal Website</title>
</head>
<body>
  <header>
    <h1>Welcome to My Personal Website</h1>
    <nav>
      <ul>
        <li><a href="#about-me">About Me</a></li>
        <li><a href="#my-projects">My Projects</a></li>
        <li><a href="#contact-me">Contact Me</a></li>
      </ul>
    </nav>
  </header>
  
  <main>
    <section id="about-me">
      <h2>About Me</h2>
      <p>Insert your personal introduction here.</p>
    </section>
    
    <section id="my-projects">
      <h2>My Projects</h2>
      <ul>
        <li><a href="#">Project 1</a></li>
        <li><a href="#">Project 2</a></li>
        <li><a href="#">Project 3</a></li>
      </ul>
    </section>
    
    <section id="contact-me">
      <h2>Contact Me</h2>
      <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name"><br><br>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email"><br><br>
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" rows="4" cols="50"></textarea><br><br>
        <input type="submit" value="Send">
      </form>
    </section>
  </main>
  
  <footer>
    <p>Copyright &copy; 2023</p>
  </footer>
</body>
</html>
