<template>
  <!--Awal Bootstrap Icons -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.1/font/bootstrap-icons.css" />\
  <!--Tutup Bootstrap Icons -->
  <body>
    <section id="contact" class="card" style="justify-content-center">
      <div class="container p-5">
        <div class="row text-center">
          <div class="col text-muted">
            <h5>Contact Me</h5>
          </div>
        </div>
        <div class="row justify-content-center">
          <div class="col-md-10">
            <form>
              <div class="mb-3">
                <label for="name" class="text-muted">Your Name</label>
                <input type="text" class="form-control" id="name" aria-describedby="name" />
              </div>
              <div class="mb-3">
                <label for="email" class="text-muted">Email</label>
                <input type="email" class="form-control" id="email" aria-describedby="email" />
              </div>
              <div class="mb-3">
                <label for="password" class="text-muted">Password</label>
                <input type="password" class="form-control" id="password" />
              </div>
              <div class="mb-3">
                <label for="pesan" class="text-muted">Message</label>
                <textarea class="form-control" id="pesan" rows="3"></textarea>
              </div>
              <button type="submit" class="btn btn-dark">Kirim</button>
            </form>
          </div>
        </div>
      </div>
    </section>
    <!-- Akhir Section -->
  </body>
  <!-- Awal Section -->

  <!-- Awal Wave -->
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
    <path
      fill="#212529"
      fill-opacity="0.7"
      d="M0,256L60,240C120,224,240,192,360,160C480,128,600,96,720,117.3C840,139,960,213,1080,229.3C1200,245,1320,203,1380,181.3L1440,160L1440,320L1380,320C1320,320,1200,320,1080,320C960,320,840,320,720,320C600,320,480,320,360,320C240,320,120,320,60,320L0,320Z"
    ></path>
  </svg>
  <!-- Akhir Wave -->
  <!-- Awal Footer -->
  <footer class="text-white text-center p-3">
    <p>This page is created with <i class="bi bi-suit-heart-fill"></i> by <a href="https://www.instagram.com/mhderdnsyh/" class="text-white fw-bold">mhderdnsyh</a></p>
  </footer>
  <!-- Akhir Footer -->
</template>

<style>
h5 {
  margin-top: -10px;
  margin-bottom: 30px;
  font-weight: 700;
  color: #728394;
  font-family: "Poppins", sans-serif;
}
.container {
  margin-bottom: 0px;
}
.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  border-radius: 5px;
  padding: 10px;
  margin-top: 10px;
}

section {
  margin: 250px;
  padding: 20px;
  width: 60%;
  overflow: auto;
  float: center;
  margin-bottom: 0px;
}

footer {
  margin-top: -6%;
  position: relative;
}
</style>
