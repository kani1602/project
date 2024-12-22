# Project Responsive Web Design using Bootstrap
# Date:7/12/24
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribbble Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="#">Dribbble Clone</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="home.html">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="discover.html">Discover</a></li>
          <li class="nav-item"><a class="nav-link" href="project.html">Projects</a></li>
          <li class="nav-item"><a class="nav-link" href="signup.html">Sign Up</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <header class="bg-light text-center py-5">
    <div class="container">
      <h1 class="display-4">Showcase Your Creative Work</h1>
      <p class="lead">Join the community of amazing designers and developers.</p>
      <a href="#" class="btn btn-primary btn-lg">Get Started</a>
    </div>
  </header>

  <!-- Showcase Section -->
  <section class="py-5">
    <div class="container">
      <h2 class="text-center mb-4">Explore Creative Work</h2>
      <div class="row">
        <div class="col-md-4">
          <div class="card mb-4">
            <img src="ui-example-round-corners-trend.avif" class="card-img-top" alt="Project 1" height="350">
            <div class="card-body">
              <h5 class="card-title">Mobile UI Design Examples</h5>
              <p class="card-text">A stunning user interface design for a modern application.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card mb-4">
            <img src="project2.jpg" class="card-img-top" alt="Project 2" height="350">
            <div class="card-body">
              <h5 class="card-title">Creative portfolio Design</h5>
              <p class="card-text">An artistic portfolio showcasing vibrant creativity.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card mb-4">
            <img src="innovation.jpg" class="card-img-top" alt="Project 3" height="350">
            <div class="card-body">
              <h5 class="card-title">The Future of Design: Blending Creativity, Technology, and Innovation</h5>
              <p class="card-text">A tech-driven design concept for future innovation.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Call-to-Action Section -->
  <section class="bg-primary text-white text-center py-5">
    <div class="container">
      <h2 class="mb-3">Ready to Join?</h2>
      <p class="lead">Sign up today and share your creativity with the world.</p>
      <a href="#" class="btn btn-light btn-lg">Sign Up</a>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-light text-center py-3">
    <div class="container">
      <p class="mb-0">Designed by Mahajananigaja</p>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Discover Projects</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }

        header {
            background-color: #007bff;
            color: white;
            padding: 15px 20px;
            text-align: center;
        }

        .container {
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .project {
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }

        .project img {
            max-width: 100%;
            border-radius: 8px;
            margin-bottom: 15px;
        }

        .project h2 {
            margin: 0 0 10px;
            font-size: 20px;
            color: #333;
        }

        .project p {
            font-size: 14px;
            color: #555;
            margin: 0 0 15px;
        }

        .project a {
            display: inline-block;
            padding: 10px 15px;
            background-color: #007bff;
            color: white;
            text-decoration: none;
            border-radius: 4px;
            font-size: 14px;
        }

        .project a:hover {
            background-color: #0056b3;
        }

        footer {
            text-align: center;
            padding: 15px;
            background-color: #f1f1f1;
            color: #777;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Discover Projects</h1>
    </header>

    <div class="container">
        <div class="project">
            <img src="project1.jpg" alt="Project 1" height="200" width="200">
            <h2>Creative portfolio Design</h2>
            <p>An artistic portfolio showcasing vibrant creativity.</p>
            <a href="#">View More</a>
        </div>

        <div class="project">
            <img src="project2.jpg" alt="Project 2">
            <h2>The Future of Design: Blending Creativity, Technology, and Innovation</h2>
            <p>A stunning user interface design for a modern application.</p>
            <a href="#">View More</a>
        </div>

       
    </div>

    <footer>
        <p>&copy; 2024 Discover Projects. All rights reserved.</p>
    </footer>
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Projects - Dribbble Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="index.html">Dribbble Clone</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="discover.html">Discover</a></li>
          <li class="nav-item"><a class="nav-link" href="projects.html">Projects</a></li>
          <li class="nav-item"><a class="nav-link" href="signup.html">Sign Up</a></li>
        </ul>
      </div>
    </div>
  </nav>
  <header class="text-center py-5 bg-light">
    <h1>Our Projects</h1>
    <p>Check out some of the most exciting projects from our community.</p>
  </header>
  <footer class="text-center py-3 bg-light">
    <p>Designed by Mahajanani.R</p>
  </footer>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign-Up Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
        }

        .signup-container {
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 100%;
            max-width: 400px;
        }

        .signup-container h1 {
            text-align: center;
            margin-bottom: 20px;
            font-size: 24px;
            color: #333;
        }

        .form-group {
            margin-bottom: 15px;
        }

        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-size: 14px;
            color: #555;
        }

        .form-group input {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 14px;
        }

        .form-group input:focus {
            border-color: #007bff;
            outline: none;
        }

        .signup-btn {
            width: 100%;
            padding: 10px;
            background-color: #007bff;
            color: #fff;
            border: none;
            border-radius: 4px;
            font-size: 16px;
            cursor: pointer;
        }

        .signup-btn:hover {
            background-color: #0056b3;
        }

        .signup-container p {
            text-align: center;
            margin-top: 15px;
            font-size: 14px;
        }

        .signup-container a {
            color: #007bff;
            text-decoration: none;
        }

        .signup-container a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="signup-container">
        <h1>Sign Up</h1>
        <form action="/submit-signup" method="POST">
            <div class="form-group">
                <label for="username">Username</label>
                <input type="text" id="username" name="username" required>
            </div>
            <div class="form-group">
                <label for="email">Email</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="password">Password</label>
                <input type="password" id="password" name="password" required>
            </div>
            <button type="submit" class="signup-btn">Sign Up</button>
        </form>
        <p>Already have an account? <a href="/login">Log in</a></p>
    </div>
</body>
```

# OUTPUT:
![Screenshot 2024-12-22 232853](https://github.com/user-attachments/assets/b82a49af-178b-42c3-8e85-1e73f002f4ec)
![Screenshot 2024-12-22 232912](https://github.com/user-attachments/assets/44b195f4-3aab-4be9-b697-0e6e766849b4)
![Screenshot 2024-12-22 232936](https://github.com/user-attachments/assets/e986be38-f69c-4c5b-823d-585647b4ef67)
![Screenshot 2024-12-22 232952](https://github.com/user-attachments/assets/fb4e1625-4c71-4aab-9e93-f230e4bab5df)
![Screenshot 2024-12-22 233102](https://github.com/user-attachments/assets/ac64c8d1-dd72-4869-b51d-8efb180b02ae)
![Screenshot 2024-12-22 233117](https://github.com/user-attachments/assets/389a5c7b-eae0-4b27-bb31-f37e19a89592)


# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
