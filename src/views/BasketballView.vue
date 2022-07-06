<template>
  <body>
    <section id="about" class="about">
      <div class="container" data-aos="fade-up">
        <div class="section-title">
          <h4 class="text-dark"></h4>
          <p></p>
        </div>

        <div class="row">
          <div class="col-md-4 py-4 card">
            <img src="../assets/img/profile-img.jpg" class="img-fluid mx-auto d-block" />
          </div>
          <div class="col-lg-8 pt-4 pt-lg-0 content">
            <h3 class="fw-bold">Basketball Pleyah.</h3>
            <p>
              Kenalin nama saya Muhammad Erdiansyah, saya mempunyai hobi dengan dunia olahraga yaitu basket, karena saya mendalami dunia tersebut, saya jadi tau bagaimana saya bermain tiap harinya dan menurut saya hobi bukanlah sekedar
              identitas melainkan sebuah roda kehidupan saya.
            </p>

            <p>
              Basket adalah salah satu hobi yang amat saya gemari, dengan bermain basket itulah saya dapat mengoptimalkan pikiran saya selagi ada waktu senggang, sesekali ketika saya sedang bosan karena terus- terusan ngoding, saya
              sempatkan untuk bermain basket bersama teman-teman. Karena bola basket mempunyai semua yang saya mau. Kekeluargaan, kerjasama, kekompakan, kerjakeras. Karena semua ini akan tetap menjadi rutinitas untuk tetap berjuang.
            </p>
            <section id="skills" class="skills section-bg py-4 card">
              <div class="container" data-aos="fade-up">
                <div class="section-title">
                  <h3 class="fw-bold text-center">Skills</h3>
                </div>

                <div class="row skills-content">
                  <div class="col-lg-6">
                    <div class="progress">
                      <span class="skill">Ball Handling <i class="val">80%</i></span>
                      <div class="progress-bar-wrap">
                        <div class="progress-bar" role="progressbar" style="width: 80%" aria-valuenow="100" aria-valuemin="0" aria-valuemax="80"></div>
                      </div>
                    </div>

                    <div class="progress">
                      <span class="skill">Shooting <i class="val">90%</i></span>
                      <div class="progress-bar-wrap">
                        <div class="progress-bar" role="progressbar" style="width: 90%" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100"></div>
                      </div>
                    </div>

                    <div class="progress">
                      <span class="skill">Between the legs <i class="val">75%</i></span>
                      <div class="progress-bar-wrap">
                        <div class="progress-bar" role="progressbar" style="width: 75%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
                      </div>
                    </div>
                  </div>

                  <div class="col-lg-6">
                    <div class="progress">
                      <span class="skill">Passing <i class="val">80%</i></span>
                      <div class="progress-bar-wrap">
                        <div class="progress-bar" role="progressbar" style="width: 80%" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100"></div>
                      </div>
                    </div>

                    <div class="progress">
                      <span class="skill">Ankle Break <i class="val">90%</i></span>
                      <div class="progress-bar-wrap">
                        <div class="progress-bar" role="progressbar" style="width: 90%" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100"></div>
                      </div>
                    </div>

                    <div class="progress">
                      <span class="skill">Defense <i class="val">55%</i></span>
                      <div class="progress-bar-wrap">
                        <div class="progress-bar" role="progressbar" style="width: 55%" aria-valuenow="55" aria-valuemin="0" aria-valuemax="100"></div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </section>
          </div>
        </div>
      </div>
    </section>
    <!-- End About Section -->
  </body>

  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
    <path
      fill="#212529"
      fill-opacity="0.7"
      d="M0,256L60,240C120,224,240,192,360,160C480,128,600,96,720,117.3C840,139,960,213,1080,229.3C1200,245,1320,203,1380,181.3L1440,160L1440,320L1380,320C1320,320,1200,320,1080,320C960,320,840,320,720,320C600,320,480,320,360,320C240,320,120,320,60,320L0,320Z"
    ></path>
  </svg>
  <!-- Awal Footer -->
  <footer class="text-white text-center p-3">
    <p>Page Basketball <a href="https://www.instagram.com/mhderdnsyh/" class="text-white fw-bold">mhderdnsyh</a></p>
  </footer>
  <!-- Akhir Footer -->
</template>

<style>
/*--------------------------------------------------------------
# About
--------------------------------------------------------------*/

.about .content h3 {
  font-weight: 700;
  font-size: 26px;
  color: #728394;
  font-family: "Poppins", sans-serif;
}
.progress-bar {
  color: #728394;
}
.about {
  margin-top: 40px;
}
body {
  color: black;
  text-align: justify;
}

.skills .progress {
  height: 60px;
  display: block;
  background: none;
  border-radius: 0;
}
.skills .progress .skill {
  padding: 10px 0;
  margin: 0;
  text-transform: uppercase;
  display: block;
  font-weight: 600;
  font-family: "Poppins", sans-serif;
  color: #45505b;
}
.skills .progress .skill .val {
  float: right;
  font-style: normal;
}
.skills .progress-bar-wrap {
  background: #f2f3f5;
}
.skills .progress-bar {
  width: 1px;
  height: 10px;
  transition: 0.9s;
  background-color: #0563bb;
}
footer {
  margin-top: -6%;
  position: relative;
}
</style>
