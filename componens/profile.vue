<template>
    <div class="container mt-5">
      <!-- Profile Header -->
      <div class="profile-header text-center mb-5">
        <img src="https://via.placeholder.com/150" alt="Profile Image" class="rounded-circle profile-img" />
        <h2 class="mt-3">Aditya Putra Manunggal</h2>
        <p class="text-muted">Software Engineer | Web Developer | Technology Enthusiast</p>
        <div class="social-icons mt-3">
          <NuxtLink to="#" class="btn btn-outline-primary btn-sm"><i class="fab fa-twitter"></i></NuxtLink>
          <NuxtLink to="#" class="btn btn-outline-info btn-sm"><i class="fab fa-linkedin"></i></NuxtLink>
          <NuxtLink to="#" class="btn btn-outline-dark btn-sm"><i class="fab fa-github"></i></NuxtLink>
          <NuxtLink to="#" class="btn btn-outline-danger btn-sm"><i class="fab fa-instagram"></i></NuxtLink>
        </div>
      </div>
  
      <!-- Profile Content -->
      <div class="row">
        <!-- Left Sidebar - Profile Info -->
        <div class="col-md-4">
          <div class="card shadow-lg profile-card">
            <div class="card-body text-center">
              <h5 class="card-title">Profile Info</h5>
              <p class="card-text">
                Aditya Putra is a student at the Vocational Faculty of Information Technology Study Program who is working on Pak Wildan's assignment to create a profile/CV.
              </p>
              <hr />
              <p><strong>Lokasi:</strong> Malang, Indonesia</p>
              <p><strong>Email:</strong> newaditya6@gmail.com</p>
              <p><strong>No Hp:</strong> 081554668378</p>
            </div>
          </div>
  
          <!-- Skills Card -->
          <div class="card shadow-lg mt-4 profile-card">
            <div class="card-body">
              <h5 class="card-title">Skills</h5>
              <ul class="skills-list">
                <li>Ilmu Pengetahuan Alam: Dasar fisika, kimia, dan biologi.</li>
                <li>Keterampilan Laboratorium: Penggunaan alat dan metode ilmiah dalam eksperimen.</li>
                <li>Pengenalan Karir STEM: Pengetahuan tentang jalur karir di bidang sains, teknologi, dan teknik.</li>
                <li>Java, Python, SQL</li>
              </ul>
            </div>
          </div>
        </div>
  
        <!-- Right Sidebar - About Me, Experience, Education -->
        <div class="col-md-8">
          <!-- About Me Section -->
          <div class="card shadow-lg profile-info-card mb-4">
            <div class="card-header bg-primary text-white">About Me</div>
            <div class="card-body">
              <p>
                Hi, I'm Aditya, a student at Brawijaya University, class of 2023, vocational faculty, information technology study program, I graduated from SMA Negeri 1 Bluluk in Lamongan Regency, majoring in Mathematics and Natural Sciences.
              </p>
            </div>
          </div>
  
          <!-- Experience Section -->
          <div class="card shadow-lg profile-info-card mb-4">
            <div class="card-header bg-primary text-white">Experience</div>
            <div class="card-body">
              <h5>Senior Software Engineer</h5>
              <p class="text-muted">Tech Solutions Ltd. - Jan 2020 - Present</p>
              <ul>
                <li>Lead a team of 8 developers in building a large-scale e-commerce platform.</li>
                <li>Designed and implemented RESTful APIs using Node.js and Express.</li>
                <li>Collaborated with the frontend team to integrate Vue.js into the web application.</li>
              </ul>
  
              <h5>Full Stack Developer</h5>
              <p class="text-muted">Web Innovators Inc. - Jul 2017 - Dec 2019</p>
              <ul>
                <li>Developed and maintained several websites using React, Bootstrap, and Node.js.</li>
                <li>Managed database operations with MongoDB and SQL databases.</li>
                <li>Optimized web application performance and improved page load times by 30%.</li>
              </ul>
            </div>
          </div>
  
          <!-- Education Section -->
          <div class="card shadow-lg profile-info-card mb-4">
            <div class="card-header bg-primary text-white">Education</div>
            <div class="card-body">
              <p class="text-muted">SMA NEGRI 1 BLULUK</p>
              <p>passed with good grades.</p>
            </div>
          </div>
  
          <!-- Contact Section -->
          <div class="card shadow-lg profile-info-card">
            <div class="card-header bg-primary text-white">Contact Me</div>
            <div class="card-body">
              <p>Feel free to reach out to me for project collaborations, job opportunities, or just to connect!</p>
              <form>
                <div class="mb-3">
                  <label for="contactName" class="form-label">Name</label>
                  <input type="text" class="form-control" id="contactName" required />
                </div>
                <div class="mb-3">
                  <label for="contactEmail" class="form-label">Email</label>
                  <input type="email" class="form-control" id="contactEmail" required />
                </div>
                <div class="mb-3">
                  <label for="contactMessage" class="form-label">Message</label>
                  <textarea class="form-control" id="contactMessage" rows="4" required></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Send Message</button>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script setup>
  // No additional script logic needed for this static page.
  </script>
  
  <style>
  /* Custom CSS can go here, like from the original 'styles.css' */
  </style> 