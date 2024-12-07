# Landing-page.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ISH Dance Academy</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Header Section -->
  <header>
    <h1>ISH DANCE ACADEMY</h1>
    <p>Dance is more than just physical activity,it's a Celebration of creativity and Connection.</p>
    <a href="#learn-more" class="cta-button">Learn More</a>
  </header>

  <!-- Main Section -->
  <main>
    <!-- Section 1: About -->
    <section id="about">
      <h2>About Us</h2>
      <p>We do choreography for Sangeet, events, Parties and Marriages.</p>
    </section>

    <!-- Section 2: Services -->
    <section id="services">
      <h2>WE TEACH</h2>
      <div class="services-container">
        <div class="service-box">
          <h3>Dance form 1</h3>
          <p>Indian Classical</p>
        </div>
        <div class="service-box">
          <h3>Dance form 2</h3>
          <p>Western Dance</p>
        </div>
        <div class="service-box">
          <h3>Dance form 3</h3>
          <p>Kathak</p>
        </div>
      </div>
    </section>
  </main>

  <!-- Footer Section -->
  <footer>
    <p>&copy; ISH dance Academy.</p>
    <p>Follow us on social media!</p>
  </footer>
</body>
</html>




#Landing page.css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
  }
  
  /* Header Styles */
  header {
    background-color: #e20faa;
    color: white;
    padding: 2rem;
    text-align: center;
  }
  
  header h1 {
    margin-bottom: 0.5rem;
  }
  
  header p {
    font-size: 1.2rem;
    margin-bottom: 1rem;
  }
  
  .cta-button {
    text-decoration: none;
    background-color: #333;
    color: white;
    padding: 0.75rem 1.5rem;
    border-radius: 5px;
    transition: background-color 0.3s;
  }
  
  .cta-button:hover {
    background-color: #555;
  }
  
  /* Main Content Styles */
  main {
    padding: 2rem;
  }
  
  section {
    margin-bottom: 2rem;
    text-align: center;
  }
  
  .services-container {
    display: flex;
    justify-content: space-around;
    gap: 1rem;
  }
  
  .service-box {
    background-color: #f4f4f4;
    padding: 1rem;
    border-radius: 5px;
    width: 30%;
  }
  
  .service-box h3 {
    margin-bottom: 0.5rem;
  }
  
  /* Footer Styles */
  footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem;
  }
  
  /* Responsive Design */
  @media (max-width: 768px) {
    .services-container {
      flex-direction: column;
    }
  
    .service-box {
      width: 100%;
    }
  }
  
