# Project Responsive Web Design using Bootstrap
## Date:17-11-2025

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
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .hero {
            padding: 80px 0;
            background-color: #fce7ef;
            text-align: center;
        }
        .placeholder-box {
            height: 180px;
            background: #e5e5e5;
            border-radius: 10px;
        }
        footer {
            background: #222;
            color: #ccc;
            padding: 30px 0;
            font-size: 14px;
        }
    </style>
</head>
<body>

<!-- NAVIGATION -->
<nav class="navbar navbar-expand-lg navbar-light bg-light py-3">
    <div class="container">
        <a class="navbar-brand fw-bold" href="#">Dribbble Clone</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item"><a class="nav-link" href="#">Inspiration</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Find Work</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Learn Design</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Go Pro</a></li>
                <li class="nav-item"><a class="btn btn-dark ms-3" href="#">Sign Up</a></li>
            </ul>
        </div>
    </div>
</nav>

<!-- HERO SECTION -->
<section class="hero">
    <div class="container">
        <h1 class="fw-bold display-5">Discover the world’s top designers</h1>
        <p class="lead mt-3">Explore creative work and connect with designers around the world.</p>
        <button class="btn btn-primary btn-lg mt-3">Get Started</button>
    </div>
</section>

<!-- FEATURED SHOTS -->
<section class="py-5">
    <div class="container">
        <h3 class="fw-bold mb-4">Trending Shots</h3>
        
        <div class="row g-4">
            <div class="col-md-4">
                <div class="placeholder-box"></div>
                <p class="mt-2">Design Concept</p>
            </div>
            <div class="col-md-4">
                <div class="placeholder-box"></div>
                <p class="mt-2">UI Layout</p>
            </div>
            <div class="col-md-4">
                <div class="placeholder-box"></div>
                <p class="mt-2">Brand Style</p>
            </div>
        </div>
    </div>
</section>

<!-- CALL TO ACTION -->
<section class="text-center py-5 bg-light">
    <div class="container">
        <h2 class="fw-bold">Ready to share your work?</h2>
        <p class="mt-3">Join thousands of designers showcasing their portfolios.</p>
        <button class="btn btn-dark btn-lg">Join Now</button>
    </div>
</section>

<!-- FOOTER -->
<footer>
    <div class="container text-center">
        <p>© 2025 Dribbble Clone — Built with Bootstrap</p>
    </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```


## OUTPUT:
![alt text](<Screenshot 2025-11-17 131236.png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
