# Bootstrap-Basics
Bootstrap single page class project.
# Bootstrap Registration Page

## Overview
This is a single-page website built using **Bootstrap** for a school project. The goal was to practice using Bootstrap components, layout tools, and responsive utilities. All required features are included **once** on one webpage, with no duplicated sections.

---

## Tools Used
- HTML5  
- Bootstrap 5 (via CDN)

---

## Project Files
- `index.html` — contains the entire project

No extra CSS or JavaScript files were needed.

---

## What This Page Includes

### Navigation Bar
- Responsive Bootstrap navbar
- Links to Home, About, and Contact sections
- Collapses into a hamburger menu on smaller screens

---

### Images
- One full-width responsive image using `container-fluid` and `img-fluid`
- One circular image using `rounded-circle`
- Images resize properly on all screen sizes

---

### Registration Form
- Built with Bootstrap form components
- Includes:
  - First Name and Last Name (side-by-side using the grid)
  - Email (required)
  - Password (required)
  - Terms and conditions checkbox
- Submit button styled with `btn-success`

---

### Data Table
- Bootstrap table with hard-coded sample user data
- Uses striped and hoverable rows
- Wrapped in a `table-responsive` container for smaller screens

---

### Responsiveness
- Uses Bootstrap containers and utilities for layout
- Fully responsive on mobile, tablet, and desktop screens
- Each required section appears only once

---

## How to View the Page
1. Download or clone the repository
2. Open `index.html` in any web browser
3. That’s it — no setup required

---

## Notes
- Bootstrap is loaded using a CDN, so an internet connection is needed
- This project meets all assignment requirements using one webpage

On Sat, Feb 7, 2026, 6:28 PM Diana Berra <diannamberra@gmail.com> wrote:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Bootstrap Project</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <!-- Bootstrap CSS CDN -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand" href="#">MySite</a>

    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarMenu">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarMenu">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- Image Section -->
<div class="container-fluid p-0">
  <img src="https://picsum.photos/1200/400" class="img-fluid w-100" alt="Main Banner">
</div>

<div class="container text-center my-4">
  <img src="https://picsum.photos/200" class="rounded-circle mb-3" alt="Profile Image">
</div>

<!-- Registration Form -->
<div class="container my-5" id="home">
  <h2 class="mb-4">Registration Form</h2>

  <form>
    <div class="row mb-3">
      <div class="col-md-6">
        <label class="form-label">First Name</label>
        <input type="text" class="form-control" required>
      </div>
      <div class="col-md-6">
        <label class="form-label">Last Name</label>
        <input type="text" class="form-control" required>
      </div>
    </div>

    <div class="mb-3">
      <label class="form-label">Email</label>
      <input type="email" class="form-control" required>
    </div>

    <div class="mb-3">
      <label class="form-label">Password</label>
      <input type="password" class="form-control" required>
    </div>

    <div class="form-check mb-3">
      <input class="form-check-input" type="checkbox" required>
      <label class="form-check-label">I agree to the terms and conditions</label>
    </div>

    <button type="submit" class="btn btn-success">Submit</button>
  </form>
</div>

<!-- Table Section -->
<div class="container my-5" id="about">
  <h2 class="mb-3">Registered Users</h2>

  <div class="table-responsive">
    <table class="table table-striped table-hover">
      <thead class="table-dark">
        <tr>
          <th>First Name</th>
          <th>Last Name</th>
          <th>Email</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Jane</td>
          <td>Doe</td>
          <td>jane@example.com</td>
        </tr>
        <tr>
          <td>John</td>
          <td>Smith</td>
          <td>john@example.com</td>
        </tr>
        <tr>
          <td>Alice</td>
          <td>Brown</td>
          <td>alice@example.com</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

<!-- Contact Section -->
<div class="container my-5" id="contact">
  <h2>Contact</h2>
  <p>Email: contact@example.com</p>
</div>

<!-- Bootstrap JS CDN -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>

On Sat, Feb 7, 2026, 6:25 PM Diana Berra <diannamberra@gmail.com> wrote:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Bootstrap Project</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <!-- Bootstrap CSS CDN -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand" href="#">MySite</a>

    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarMenu">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarMenu">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- Image Section -->
<div class="container-fluid p-0">
  <img src="https://picsum.photos/1200/400" class="img-fluid w-100" alt="Main Banner">
</div>

<div class="container text-center my-4">
  <img src="https://picsum.photos/200" class="rounded-circle mb-3" alt="Profile Image">
</div>

<!-- Registration Form -->
<div class="container my-5" id="home">
  <h2 class="mb-4">Registration Form</h2>

  <form>
    <div class="row mb-3">
      <div class="col-md-6">
        <label class="form-label">First Name</label>
        <input type="text" class="form-control" required>
      </div>
      <div class="col-md-6">
        <label class="form-label">Last Name</label>
        <input type="text" class="form-control" required>
      </div>
    </div>

    <div class="mb-3">
      <label class="form-label">Email</label>
      <input type="email" class="form-control" required>
    </div>

    <div class="mb-3">
      <label class="form-label">Password</label>
      <input type="password" class="form-control" required>
    </div>

    <div class="form-check mb-3">
      <input class="form-check-input" type="checkbox" required>
      <label class="form-check-label">I agree to the terms and conditions</label>
    </div>

    <button type="submit" class="btn btn-success">Submit</button>
  </form>
</div>

<!-- Table Section -->
<div class="container my-5" id="about">
  <h2 class="mb-3">Registered Users</h2>

  <div class="table-responsive">
    <table class="table table-striped table-hover">
      <thead class="table-dark">
        <tr>
          <th>First Name</th>
          <th>Last Name</th>
          <th>Email</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Jane</td>
          <td>Doe</td>
          <td>jane@example.com</td>
        </tr>
        <tr>
          <td>John</td>
          <td>Smith</td>
          <td>john@example.com</td>
        </tr>
        <tr>
          <td>Alice</td>
          <td>Brown</td>
          <td>alice@example.com</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

<!-- Contact Section -->
<div class="container my-5" id="contact">
  <h2>Contact</h2>
  <p>Email: contact@example.com</p>
</div>

<!-- Bootstrap JS CDN -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>

On Sat, Feb 7, 2026, 6:22 PM Diana Berra <diannamberra@gmail.com> wrote:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Bootstrap Project</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <!-- Bootstrap CSS CDN -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand" href="#">MySite</a>

    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarMenu">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarMenu">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- Image Section -->
<div class="container-fluid p-0">
  <img src="https://picsum.photos/1200/400" class="img-fluid w-100" alt="Main Banner">
</div>

<div class="container text-center my-4">
  <img src="https://picsum.photos/200" class="rounded-circle mb-3" alt="Profile Image">

  <div>
    <button class="btn btn-primary me-2">Always Visible Button</button>
    <button class="btn btn-warning d-none d-md-block">Hidden on Small Screens</button>
  </div>
</div>

<!-- Registration Form -->
<div class="container my-5" id="home">
  <h2 class="mb-4">Registration Form</h2>

  <form>
    <div class="row mb-3">
      <div class="col-md-6">
        <label class="form-label">First Name</label>
        <input type="text" class="form-control" required>
      </div>
      <div class="col-md-6">
        <label class="form-label">Last Name</label>
        <input type="text" class="form-control" required>
      </div>
    </div>

    <div class="mb-3">
      <label class="form-label">Email</label>
      <input type="email" class="form-control" required>
    </div>

    <div class="mb-3">
      <label class="form-label">Password</label>
      <input type="password" class="form-control" required>
    </div>

    <div class="form-check mb-3">
      <input class="form-check-input" type="checkbox" required>
      <label class="form-check-label">I agree to the terms and conditions</label>
    </div>

    <button type="submit" class="btn btn-success">Submit</button>
  </form>
</div>

<!-- Table Section -->
<div class="container my-5" id="about">
  <h2 class="mb-3">Registered Users</h2>

  <div class="table-responsive">
    <table class="table table-striped table-hover">
      <thead class="table-dark">
        <tr>
          <th>First Name</th>
          <th>Last Name</th>
          <th>Email</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Jane</td>
          <td>Doe</td>
          <td>jane@example.com</td>
        </tr>
        <tr>
          <td>John</td>
          <td>Smith</td>
          <td>john@example.com</td>
        </tr>
        <tr>
          <td>Alice</td>
          <td>Brown</td>
          <td>alice@example.com</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

<!-- Contact Section -->
<div class="container my-5" id="contact">
  <h2>Contact</h2>
  <p>Email: contact@example.com</p>
</div>

<!-- Bootstrap JS CDN -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
