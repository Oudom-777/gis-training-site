# gis-training-site
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>1-Week GIS Training</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>1-Week GIS Training</h1>
    <p>Master the fundamentals of Geographic Information Systems in just one week!</p>
  </header>

  <nav>
    <a href="#schedule">Schedule</a>
    <a href="#register">Register</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="schedule">
    <h2>Training Schedule</h2>
    <ul id="schedule-list"></ul>
  </section>

  <section id="register">
    <h2>Register Now</h2>
    <form id="registration-form">
      <input type="text" placeholder="Full Name" required />
      <input type="email" placeholder="Email Address" required />
      <button type="submit">Submit</button>
    </form>
    <p id="confirmation-message"></p>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: <a href="mailto:gis@training.com">gis@training.com</a></p>
    <p>Phone: +123-456-7890</p>
  </section>

  <footer>
    <p>&copy; 2025 GIS Training. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
body 
{
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
  background: #f4f4f4;
  color: #333;
}

header {
  background: #005f73;
  color: white;
  padding: 20px;
  text-align: center;
}

nav {
  background: #0a9396;
  display: flex;
  justify-content: center;
  padding: 10px 0;
}

nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
  font-weight: bold;
}

section {
  padding: 20px;
  max-width: 800px;
  margin: auto;
  background: white;
  margin-top: 10px;
  border-radius: 5px;
}

form {
  display: flex;
  flex-direction: column;
}

input, button {
  padding: 10px;
  margin: 10px 0;
  font-size: 16px;
}

button {
  background: #94d2bd;
  border: none;
  cursor: pointer;
}

button:hover {
  background: #0a9396;
  color: white;
}

footer {
  text-align: center;
  padding: 15px;
  background: #005f73;
  color: white;
  margin-top: 20px;
}
