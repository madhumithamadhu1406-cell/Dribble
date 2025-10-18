# Project Responsive Web Design using Bootstrap
## Date:17-10-2025

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dribbble Clone</title>

  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>


  <nav class="navbar navbar-expand-lg bg-light border-bottom sticky-top">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">Dribbble Clone</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link active" href="#">Inspiration</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Find Work</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Learn Design</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Go Pro</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Sign in</a></li>
          <li class="nav-item">
            <a class="btn btn-dark ms-2" href="#">Sign up</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>


  <section class="py-5 text-center bg-light">
    <div class="container">
      <h1 class="display-5 fw-bold">Discover the world’s top designers & creatives</h1>
      <p class="lead">Dribbble is the leading destination to find & showcase creative work.</p>
      <a href="#" class="btn btn-dark btn-lg mt-3">Get Started</a>
    </div>
  </section>

  <section class="py-5">
    <div class="container">
      <h2 class="mb-4 text-center fw-bold">Explore Shots</h2>
      <div class="row g-4">
        <div class="col-6 col-md-4 col-lg-3">
          <div class="card">
            <img src="image a.jpg" class="card-img-top" alt="Shot 1">
          </div>
        </div>
        <div class="col-6 col-md-4 col-lg-3">
          <div class="card">
            <img src="image b.jpg"card-img-top" alt="Shot 2">
          </div>
        </div>
        <div class="col-6 col-md-4 col-lg-3">
          <div class="card">
            <img src="image c.jpg" class="card-img-top" alt="Shot 3">
        </div>
        <div class="col-6 col-md-4 col-lg-3">
          <div class="card">
            <img src="image d.jpg" class="card-img-top" alt="Shot 4">
          </div>
        </div>
        <div class="col-6 col-md-4 col-lg-3">
          <div class="card">
            <img src="image e.jpg" class="card-img-top" alt="Shot 5">
          </div>
        </div>
        <div class="col-6 col-md-4 col-lg-3">
          <div class="card">
            <img src="image f.jpg" class="card-img-top" alt="Shot 6">
          </div>
        </div>
    </div>
  </section>

  <section class="py-5 bg-dark text-white text-center">
    <div class="container">
      <h2 class="fw-bold">Join the world’s leading design community</h2>
      <p class="lead mb-4">Sign up today and showcase your work to millions of creatives.</p>
      <a href="#" class="btn btn-light btn-lg">Sign Up Free</a>
    </div>
  </section>

  <footer class="py-4 bg-light border-top text-center">
    <div class="container">
      <p class="mb-0">© 2025 Dribbble Clone | Designed by <strong>Madhumitha V</strong></p>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


```

## OUTPUT:
![alt text](<Screenshot 2025-10-17 222804.png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
