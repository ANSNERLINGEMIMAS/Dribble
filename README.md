# Project Responsive Web Design using Bootstrap
## Date:27.12.2024

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
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribbble Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <div class="container-fluid">
      <a class="navbar-brand fw-bold" href="#">Dribbble</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link" href="#">Shots</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Community</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Jobs</a>
          </li>
        </ul>
        <form class="d-flex ms-auto">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-light" type="submit">Search</button>
        </form>
        <a class="btn btn-light text-primary ms-2" href="#">Sign Up</a>
        <a class="btn btn-light text-primary ms-2" href="#">Sign In</a>
      </div>
    </div>
  </nav>

  <!-- Additional Gray Bar -->
  <div class="bg-secondary py-2 text-center text-white">
    <div class="container">
      <span class="text-white">What are you working for?</span>
    </div>
  </div>

  <!-- Hero Section -->
  <section class="bg-light py-5 text-center">
    <div class="container">
      <h1 class="display-4 fw-bold">Dribble is showing and tell for Designers</h1>
      <p class="lead text-muted">Sign in for the full experience</p>
      <a href="#" class="btn btn-primary btn-lg">Get Started</a>
    </div>
  </section>

  <!-- Content Section -->
  <section class="py-5">
    <div class="container">
      <div class="row">
        <div class="col-md-4">
          <div class="card shadow-sm">
            <img src="dribble 1.webp" class="card-img-top" alt="Sample Shot">
            <div class="card-body">
              <i class="fas fa-eye"></i> 1,177
              <i class="fas fa-comments"></i> 4
              <i class="fas fa-heart"></i> 102
              <h5 class="card-title">Design Shot 1</h5>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shadow-sm">
            <img src="dribble2.webp" class="card-img-top" alt="Sample Shot">
            <div class="card-body">
              <i class="fas fa-eye"></i> 1,455
              <i class="fas fa-comments"></i> 9
              <i class="fas fa-heart"></i> 165
              <h5 class="card-title">Design Shot 2</h5>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shadow-sm">
            <img src="drib 3.webp" class="card-img-top" alt="Sample Shot">
            <div class="card-body">
              <i class="fas fa-eye"></i> 566
              <i class="fas fa-comments"></i> 9
              <i class="fas fa-heart"></i> 578
              <h5 class="card-title">Design Shot 3</h5>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-11">
    <p>&copy; @2024 DRIBBLE CLONE All rights reserved.  BY ANS NERLING EMIMA S</p>
  </footer>


  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
     
```





## OUTPUT:
![alt text](<Screenshot 2024-12-27 194454.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
