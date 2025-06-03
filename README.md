
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>ZigyasA Institute</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background-color: #f4f6f7;
    }
    header, footer {
      background-color: #1f3c88;
      color: white;
    }
    nav a {
      color: white !important;
      font-weight: bold;
    }
    .section {
      padding: 40px 20px;
    }
    .registration-form input, .registration-form select {
      margin-bottom: 15px;
    }
    .card img {
      height: 200px;
      object-fit: cover;
    }
  </style>
</head>
<body>
  <header class="text-center py-4">
    <h1>Zigyasa Coaching Centre</h1>
    <p>Empowering Future through Education</p>
  </header>

  <nav class="navbar navbar-expand-lg navbar-dark bg-primary sticky-top">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Zigyasa</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link" href="#admission">Admission</a></li>
          <li class="nav-item"><a class="nav-link" href="#registration">Registration</a></li>
          <li class="nav-item"><a class="nav-link" href="#fee">Tuition Fee</a></li>
          <li class="nav-item"><a class="nav-link" href="#calculator">Fee Calculator</a></li>
          <li class="nav-item"><a class="nav-link" href="#books">Books</a></li>
          <li class="nav-item"><a class="nav-link" href="#uniform">Uniform</a></li>
          <li class="nav-item"><a class="nav-link" href="#other">Other</a></li>
          <li class="nav-item"><a class="nav-link" href="#dashboard">Performance</a></li>
          <li class="nav-item"><a class="nav-link" href="#gallery">Gallery</a></li>
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <section id="admission" class="section">
    <div class="container">
      <h2>Admission</h2>
      <p>We offer admissions for students from Class 8 to 12 for all SCIENCE major subjects and entrance preparations.</p>
    </div>
  </section>

  <section id="registration" class="section bg-light">
    <div class="container">
      <h2>Registration</h2>
      <form action="submit.php" method="post" class="registration-form">
        <input type="text" class="form-control" name="fullname" placeholder="Full Name" required>
        <input type="text" class="form-control" name="class" placeholder="Class" required>
        <input type="tel" class="form-control" name="phone" placeholder="Phone Number" required>
        <input type="email" class="form-control" name="email" placeholder="Email">
        <input type="text" class="form-control" name="subjects" placeholder="Subjects Interested">
        <button type="submit" class="btn btn-primary w-100">Submit</button>
      </form>
    </div>
  </section>

  <section id="fee" class="section">
    <div class="container">
      <h2>Tuition Fee</h2>
      <p>Monthly fees range from ₹200 to ₹1500 depending on class and subject.</p>
    </div>
  </section>

  <section id="calculator" class="section bg-light">
    <div class="container">
      <h2>Fee Calculator</h2>
      <div class="row g-3">
        <div class="col-md-4">
          <input type="number" id="subjects" class="form-control" placeholder="Number of Subjects">
        </div>
        <div class="col-md-4">
          <input type="number" id="months" class="form-control" placeholder="Number of Months">
        </div>
        <div class="col-md-4">
          <button class="btn btn-success w-100" onclick="calculateFee()">Calculate Fee</button>
        </div>
      </div>
      <div class="mt-3" id="feeResult"></div>
    </div>
  </section>

  <section id="books" class="section">
    <div class="container">
      <h2>Books</h2>
      <p>All study materials are based on the latest curriculum and exam patterns.</p>
    </div>
  </section>

  <section id="uniform" class="section bg-light">
    <div class="container">
      <h2>Uniform</h2>
      <p>Uniform is mandatory and available at the centre for purchase.</p>
    </div>
  </section>

  <section id="other" class="section">
    <div class="container">
      <h2>Other Services</h2>
      <p>Includes scholarships, demo classes, and parent-teacher interactions.</p>
    </div>
  </section>

  <section id="dashboard" class="section bg-light">
    <div class="container">
      <h2>Student Performance Dashboard</h2>
      <table class="table table-bordered">
        <thead>
          <tr>
            <th>Student</th>
            <th>Math</th>
            <th>Science</th>
            <th>English</th>
          </tr>
        </thead>
        <tbody>
          <tr><td>Ankit</td><td>85</td><td>90</td><td>88</td></tr>
          <tr><td>Abhay</td><td>78</td><td>82</td><td>91</td></tr>
          <tr><td>Saurabh</td><td>92</td><td>88</td><td>84</td></tr>
        </tbody>
      </table>
    </div>
  </section>

  <section id="gallery" class="section">
    <div class="container">
      <h2>Gallery</h2>
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <img src="https://via.placeholder.com/300x200" class="card-img-top" alt="Classroom">
            <div class="card-body">Classroom Session</div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="https://via.placeholder.com/300x200" class="card-img-top" alt="Library">
            <div class="card-body">Library Facilities</div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="https://via.placeholder.com/300x200" class="card-img-top" alt="Student Activity">
            <div class="card-body">Student Activities</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="about" class="section bg-light">
    <div class="container">
      <h2>About Zigyasa Coaching Centre</h2>
      <p>Founded in 2010, Zigyasa is committed to academic excellence and holistic development of students.</p>
    </div>
  </section>

  <footer class="text-center py-3">
    &copy; 2025 Zigyasa Coaching Centre. All rights reserved.
  </footer>

  <script>
    function calculateFee() {
      const subjects = document.getElementById('subjects').value;
      const months = document.getElementById('months').value;
      const feePerSubject = 600;
      const total = subjects * months * feePerSubject;
      document.getElementById('feeResult').innerText = `Total Fee: ₹${total}`;
    }
  </script>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
