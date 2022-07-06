<template>
  <div class="about justify-content-center">
    <div class="container mt-3">
      <div class="row">
        <div class="col-md-4 py-4">
          <div id="accordion">
            <div class="card">
              <div class="card-header">
                <a class="card-link text-center" data-toggle="collapse" href="#collapseOne">
                  <img src="../assets/img/IAN.jpg" class="img-fluid mx-auto d-block" />
                </a>
              </div>
              <div id="collapseOne" class="collapse show" data-parent="#accordion">
                <div class="card-body">
                  <p><i class="fas fa-user-tie"></i> <span class="font-weight-bold">Hello Everyone,</span></p>
                  <p>
                    <i class="fas fa-map-marker-alt"></i>
                    <span class="font-weight-bold"
                      >Perkenalkan nama saya Muhammad Erdiansyah, lahir di Kota Pekanbaru pada tanggal 27 Juni 2002, berusia 20 tahun, saat ini sedang menempuh pendidikan di sebuah Universitas Islam Negeri Sultan Syarif Kasim Riau terdaftar
                      sebagai mahasiswa jurusan Teknik Informatika, alasan mendaftar karena prospek kerja...
                    </span>
                  </p>
                  <p><i class="fas fa-at"></i> <span class="font-weight-bold"></span></p>
                </div>
              </div>
              <div class="card-footer text-center"></div>
              <a href="https://mhderdnsyhh.blogspot.com/"><button class="btn btn-dark">Blog Mahasiswa</button></a>
            </div>
          </div>
        </div>

        <div class="col-md-4 py-4">
          <div id="accordion">
            <div class="card">
              <div class="card-header">
                <a class="card-link text-center" data-toggle="collapse" href="#collapseOne">
                  <img src="../assets/img/IAN2.jpg" class="img-fluid mx-auto d-block" />
                </a>
              </div>
              <div id="collapseOne" class="collapse show" data-parent="#accordion">
                <div class="card-body">
                  <p><i class="fas fa-user-tie"></i> <span class="font-weight-bold">Teknik Informatika,</span></p>
                  <p>
                    <i class="fas fa-map-marker-alt"></i>
                    <span class="font-weight-bold"
                      >Teknik Informatika merupakan bidang ilmu yang mempelajari bagaimana menggunakan teknologi komputer secara optimal guna menangani masalah transformasi atau pengolahan data dengan proses logika. Di Jurusan Teknik
                      Informatika kamu akan mempelajari berbagai prinsip terkait ilmu komputer...</span
                    >
                  </p>
                  <p><i class="fas fa-at"></i> <span class="font-weight-bold"></span></p>
                </div>
              </div>
              <div class="card-footer text-center"></div>
              <a href="https://tif.uin-suska.ac.id/"><button class="btn btn-dark">Jurusan</button></a>
            </div>
          </div>
        </div>

        <div class="col-md-4 py-4">
          <div id="accordion">
            <div class="card">
              <div class="card-header">
                <a class="card-link text-center" data-toggle="collapse" href="#collapseOne">
                  <img src="../assets/img/IAN3.jpg" class="img-fluid mx-auto d-block" />
                </a>
              </div>
              <div id="collapseOne" class="collapse show" data-parent="#accordion">
                <div class="card-body">
                  <p><i class="fas fa-user-tie"></i> <span class="font-weight-bold">Fakultas Sains dan Teknologi,</span></p>
                  <p>
                    <i class="fas fa-map-marker-alt"></i>
                    <span class="font-weight-bold"
                      >Fakultas Sains dan Teknologi Informasi merupakan pengembangan dari Fakultas Matematika dan Ilmu Pengetahuan Alam. Fakultas ini memiliki 5 program studi yaitu matematika, teknik industri, teknik elektro, sistem
                      informasi, dan teknik informatika. Setiap program studi memiliki kekhususan masing...</span
                    >
                  </p>
                  <p><i class="fas fa-at"></i> <span class="font-weight-bold"></span></p>
                </div>
              </div>
              <div class="card-footer text-center"></div>
              <a href="https://fst.uin-suska.ac.id/"><button class="btn btn-dark">Fakultas</button></a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
    <path
      fill="#212529"
      fill-opacity="0.7"
      d="M0,256L60,240C120,224,240,192,360,160C480,128,600,96,720,117.3C840,139,960,213,1080,229.3C1200,245,1320,203,1380,181.3L1440,160L1440,320L1380,320C1320,320,1200,320,1080,320C960,320,840,320,720,320C600,320,480,320,360,320C240,320,120,320,60,320L0,320Z"
    ></path>
  </svg>
  <!-- Awal Footer -->
  <footer class="text-white text-center p-3">
    <p>Page About <a href="https://www.instagram.com/mhderdnsyh/" class="text-white fw-bold">mhderdnsyh</a></p>
  </footer>
  <!-- Akhir Footer -->
</template>

<style>
.about {
  color: black;
  display: grid;
  list-style-type: none;
  margin: 0;
  padding: 0;
  grid-template-columns: repeat(3, auto);
  grid-template-rows: repeat(3, auto);
}

.btn {
  margin-bottom: 25px;
  width: 100%;
  height: 100%;
}

.card-link h4,
.card-header {
  color: black;
  font-family: "Trebuchet MS";
  line-height: 2px;
}
.card-body {
  text-align: justify;
}
.card-body .fas,
.card-footer .fab {
  color: #0e3a72b0;
}
.card-footer .fab:hover {
  color: #f1bc19;
}
.card p {
  color: #503534;
}
.card-footer .fab {
  font-size: 35px !important;
  margin: 0 5px;
}
footer {
  margin-top: -6%;
  position: relative;
}
</style>
