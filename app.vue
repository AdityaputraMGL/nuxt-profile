<template>
  <div class="container mt-5">
    <!-- Profile Header -->
    <div class="profile-header text-center mb-5">
      <img src="assets/adit.png.jpg" alt="Profile Image" class="rounded-circle profile-img" />
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
            <h5></h5>
            <p class="text-muted"></p>
            <ul>
              <li>My experience was working in Sukakatsu which was in Suhat for 6 months</li>
            </ul>

            <h5></h5>
            <p class="text-muted"></p>
            <ul>
              
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

<script>
export default {
    head() {
      return {
        title: "Curriculum Vitae",
        meta: [
          { charset: "UTF-8" },
          { name: "viewport", content: "width=device-width, initial-scale=1.0" },
        ],
        link: [
          { rel: "stylesheet", href: "https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" }
        ]
      };
    }
  };
</script>

<style>
.container {
  background-color: #f0f8ff; /* Light blue background for the entire page */
  padding: 20px;
  border-radius: 10px;
}

/* Profile header styling */
.profile-header {
  background-color: #007bff; /* Primary blue background */
  padding: 30px;
  border-radius: 10px;
  color: white;
}

.profile-header h2 {
  font-size: 28px;
  font-weight: bold;
}

.profile-header p {
  font-size: 18px;
  color: #e0e0e0; /* Lighter color for subtitle */
}

.profile-img {
  border: 5px solid #fff;
  width: 150px;
  height: 150px;
}

.social-icons .btn {
  margin: 0 5px;
}

/* Card Styling */
.card {
  border: none;
  border-radius: 10px;
}

.profile-card {
  background-color: #ffffff;
  border-left: 5px solid #007bff; /* Blue border on the left side */
}

.profile-info-card {
  background-color: #f9f9f9;
  border-left: 5px solid #007bff;
}

.card-header {
  font-weight: bold;
  font-size: 18px;
}

/* Skills list styling */
.skills-list {
  list-style-type: none;
  padding-left: 0;
}

.skills-list li {
  margin-bottom: 10px;
  font-size: 16px;
}

/* About Me and other sections */
.profile-info-card .card-body {
  font-size: 16px;
  color: #4a4a4a;
}

.profile-info-card .card-header {
  background-color: #007bff; /* Primary blue background */
  color: white;
}

/* Contact Form */
input.form-control, textarea.form-control {
  border: 1px solid #007bff;
}

button.btn-primary {
  background-color: #007bff;
  border: none;
}

button.btn-primary:hover {
  background-color: #0056b3;
}

/* Responsive design adjustments */
@media (max-width: 768px) {
  .profile-header {
    padding: 20px;
  }

  .profile-img {
    width: 120px;
    height: 120px;
  }

  .profile-info-card .card-body {
    font-size: 14px;
  }
}
</style>