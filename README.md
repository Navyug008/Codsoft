# Codsoft
here, I add new project task of internship
Web development project
task1- "Landing page"
html code


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Landing Page</title>
  <link rel="stylesheet" href="task1.css">
</head>
<body>
  <header>
    <div class="top-bar">
      <div class="logo-container">
        <img src="logo.jpg" alt="company-logo" class="company-logo">
        <h1 class="company-name">NavWorld</h1>
      </div>
      <nav class="nav-buttons">
        <button>Home</button>
        <button>Service</button>
        <button>Login</button>
        <button>About Us</button>
        <button>Contact</button>
      </nav>
    </div>
    <h1>Welcome to My Landing Page</h1>
  </header>
  <section>
    <h2>About Us</h2>
    <p>Information about the company or product.</p>
    <p>For over a decade, our company has been dedicated to delivering exceptional results for our clients. 
        Our passion for excellence drives us to continuously innovate and improve, ensuring that we meet and exceed the expectations of those we serve. With a commitment to quality and a focus on achieving the best possible outcomes, we have built a reputation for reliability and success.
       Join us on our journey as we continue to strive for greatness and make a positive impact in our industry.</p>
  </section>
  <section>
    <h2>Preferences</h2>
    <form>
      <fieldset>
        <legend>Select your preferences:</legend>
        <label>
          <input type="checkbox" name="preference" value="news">
          Receive Newsletters
        </label><br>
        <label>
          <input type="checkbox" name="preference" value="updates">
          Receive Updates
        </label><br>
        <label>
          <input type="checkbox" name="preference" value="offers">
          Receive Special Offers
        </label>
      </fieldset>
      <fieldset>
        <legend>Choose your subscription plan:</legend>
        <label>
          <input type="radio" name="subscription" value="basic">
          Basic
        </label><br>
        <label>
          <input type="radio" name="subscription" value="premium">
          Premium
        </label><br>
        <label>
          <input type="radio" name="subscription" value="vip">
          VIP
        </label>
      </fieldset>
      <button type="submit">Submit</button>
    </form>
  </section>
  <footer>
    <p>Contact Information</p>
    <p>Email: info@navworld.com | Phone: (123) 456-7890</p>
    <p>Address: 123 NavWorld Street, City, Country</p>
    <p>&copy; 2023 NavWorld. All rights reserved.</p>
  </footer>
</body>
</html>

Css Code

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background-image: url('bi.jpg');
    background-size: cover; 
    background-position: center; 
    background-repeat: no-repeat; 
  }
  
  header {
    background-color: rgba(76, 175, 80, 0.8); 
    color: white;
    text-align: center;
    padding: 1em 0;
  }
  
  .top-bar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 1em;
  }
  
  .logo-container {
    display: flex;
    align-items: center;
  }
  
  .company-logo {
    height: 50px;
    width: auto;
    margin-right: 10px;
  }
  
  .company-name {
    font-size: 25px;
    color: rgb(180, 58, 58);
  }
  
  .nav-buttons button {
    background-color: #fff;
    color: #4CAF50;
    border: none;
    padding: 0.5em 1em;
    margin: 0 0.5em;
    cursor: pointer;
    font-size: 1em;
  }
  
  .nav-buttons button:hover {
    background-color: #ddd;
  }
  
  section {
    padding: 2em;
    background-color: rgba(244, 244, 244, 0.8); /* Add transparency to see the background image */
  }
  
  form {
    margin-top: 1em;
  }
  
  fieldset {
    border: 1px solid #ccc;
    padding: 1em;
    margin-bottom: 1em;
  }
  
  legend {
    font-weight: bold;
  }
  
  label {
    display: block;
    margin-bottom: 0.5em;
  }
  
  button[type="submit"] {
    background-color: #4CAF50;
    color: white;
    border: none;
    padding: 0.5em 1em;
    cursor: pointer;
    font-size: 1em;
  }
  
  button[type="submit"]:hover {
    background-color: #45a049;
  }
  
  footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1em 0;
    position: sticky;
    width: 100%;
    bottom: 0;
  }

  

