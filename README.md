# Project Responsive Web Design using Bootstrap
## Date:01.01.2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
DRIBBLE .html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DRIBBLE</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">DRIBBLE</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#home">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#gallery">Gallery</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#about">About</a>
          </li>
        </ul>
        <form class="d-flex ms-3" action="#" method="GET">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-light" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>

  <header class="bg-dark text-white text-center py-5" id="home">
    <div class="container">
      <h1 class="display-4">Welcome to Design Paradise</h1>
      <p class="lead">Explore creativity, connect with designers, and find inspiration.</p>
      <a href="#gallery" class="btn btn-primary btn-lg mt-3">Discover More</a>
    </div>
  </header>

  <section id="gallery" class="py-5 bg-light">
    <div class="container">
      <h2 class="text-center mb-4">Design Highlights</h2>
      <div class="row g-4">
        <div class="col-lg-4 col-md-6">
          <div class="card shadow-sm">
            <img src="modern design.webp" class="card-img-top" alt="Design 1">
            <div class="card-body">
              <h5 class="card-title">Modern Design</h5>
              <p class="card-text">Innovative and sleek designs for contemporary audiences.</p>
              <a href="#" class="btn btn-dark">View Project</a>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6">
          <div class="card shadow-sm">
            <img src="brand identity.webp" class="card-img-top" alt="Design 2">
            <div class="card-body">
              <h5 class="card-title">Brand Identity</h5>
              <p class="card-text">Unique branding solutions tailored to your vision.</p>
              <a href="#" class="btn btn-dark">View Project</a>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6">
          <div class="card shadow-sm">
            <img src="elegent logo.webp" class="card-img-top" alt="Design 3">
            <div class="card-body">
              <h5 class="card-title">Elegant Logos</h5>
              <p class="card-text">Professional logo designs for businesses and creators.</p>
              <a href="#" class="btn btn-dark">View Project</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="about" class="py-5">
    <div class="container text-center">
      <h2>About Us</h2>
      <p class="mt-3">At Design Paradise, we celebrate creativity and innovation. Our platform brings together the best designers and their works to inspire and connect with the world.</p>
    </div>
  </section>

  <footer class="bg-dark text-white text-center py-3">
    <p>&copy; 2025 Design Paradise. Built with passion by Praisy Nishitha.j</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


```
## OUTPUT:
![alt text](<Screenshot 2025-01-01 064908.png>)
![alt text](<Screenshot (30).png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
