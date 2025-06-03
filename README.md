
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
    <h1>ZigyasA Institute</h1>
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

  <section id="registration" class="section bg-light">
  <div class="container">
    <h2>Registration</h2>
    <form action="https://formsubmit.co/eduworld000333@gmail.com" method="POST" enctype="multipart/form-data" class="registration-form">
      <!-- Basic Info -->
      <input type="text" class="form-control" name="fullname" placeholder="Full Name" required>
      <select class="form-control" name="class" required>
  <option value="">Select Class</option>
  <option value="8th">8th</option>
  <option value="9th">9th</option>
  <option value="10th">10th</option>
  <option value="11th">11th</option>
  <option value="12th">12th</option>
</select>
      <input type="tel" class="form-control" name="phone" placeholder="Phone Number" required>
      <input type="email" class="form-control" name="email" placeholder="Email" required>

      <!-- Subjects -->
      <h5>Select Your Subjects</h5>
      <div class="mb-3">
        <label><input type="checkbox" name="subjects[]" value="Computer"> Computer</label><br>
        <label><input type="checkbox" name="subjects[]" value="Physics"> Physics</label><br>
        <label><input type="checkbox" name="subjects[]" value="Chemistry"> Chemistry</label><br>
        <label><input type="checkbox" name="subjects[]" value="Math"> Mathematics</label><br>
        <label><input type="checkbox" name="subjects[]" value="Biology"> Biology</label><br>
        <label><input type="checkbox" name="subjects[]" value="English"> English</label><br>
        <label><input type="checkbox" name="subjects[]" value="Other"> Other</label>
      </div>

      <!-- File Upload -->
      <div class="mb-3">
        <label for="photo">Upload Your Photo</label>
        <input type="file" class="form-control" name="photo" accept="image/*" required>
      </div>

      <!-- Submit -->
      <button type="submit" class="btn btn-primary w-100">Submit</button>

  <section id="fee" class="section">
    <div class="container">
      <h2>Tuition Fee</h2>
      <p>Monthly fees range from ₹200 to ₹1500, And also depending on class and subject.</p>
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
            <th>Students Name</th>
            <th>Percentage</th>
            <th>Rank in His School</th>
          </tr>
        </thead>
        <tbody>
          <tr><td>Ankit</td><td>85</td><td>SVM Nagar untari</td></tr>
          <tr><td>Abhay</td><td>78</td><td>SVM Nagar untari</td></tr>
          <tr><td>Saurabh</td><td>92</td><td>SVM Nagar untari</td></tr>
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
            <img src="C:\Users\Ajeet\Desktop\zigyasa.html/z1.jpg/300x200" class="card-img-top" alt="Classroom">
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
      <p>Founded in 20th June 2024, Zigyasa is committed to academic excellence and holistic development of students.</p>
    </div>
  </section>

  <footer class="text-center py-3">
    &copy; 2025 Zigyasa Coaching Centre. All rights reserved.
  </footer>

  <script>
    function calculateFee() {
      const subjects = document.getElementById('subjects').value;
      const months = document.getElementById('months').value;
      const feePerSubject = 200;
      const total = subjects * months * feePerSubject;
      document.getElementById('feeResult').innerText = `Total Fee: ₹${total}`;
    }
  </script>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
