---
widget: blank
weight: 10
active: false
headless: true
---
<!-- <div class="row">
    <div class="col-12 col-md-6">
        <h2>Tes</h2>
    </div>
    <div class="col-12 col-md-6">
        <h2>tes 2</h2>
    </div>
</div> -->

<!DOCTYPE html>
<html>
  <head>
    <title>Full-Screen Hero Section</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="style.css">
  </head>
  <style>
    body {
    margin: 0;
    padding: 0;
    /* font-family: Arial, sans-serif; */
    }
    .hero {
    background-image: url("media/bosscha01.jpg");
    background-size: cover;
    background-position: center;
    height: 100vh;
    width: 100vw;
    display: flex;
    justify-content: center;
    align-items: center;
    }
    .hero-text {
    text-align: center;
    color: #fff;
    }
    .hero-text h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
    }
    .hero-text p {
    font-size: 1.1rem;
    margin-bottom: 2rem;
    }
    button {
    padding: 1rem 2rem;
    background-color: #fff;
    border: none;
    color: #333;
    font-size: 1.2rem;
    cursor: pointer;
    transition: all 0.3s ease;
    }
    button:hover {
    background-color: #333;
    color: #fff;
    }

  </style>
  <body>
    <section class="hero">
      <div class="hero-text">
        <h1>Welcome to My Website</h1>
        <p>Here you will find everything you need to know about our products and services.</p>
        <button>Learn More</button>
      </div>
    </section>
  </body>
</html>
