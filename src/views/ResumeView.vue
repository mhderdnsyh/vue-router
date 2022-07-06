<template>
  <body>
    <!-- ======= Resume Section ======= -->
    <section id="resume" class="resume card mb-3" style="max-width: 70rem">
      <div class="container" data-aos="fade-up">
        <div class="section-title">
          <h2 class="text-dark"></h2>
          <p class="text-dark"></p>
        </div>

        <div class="row">
          <div class="col-lg-6">
            <h3 class="resume-title">Sumary</h3>
            <div class="resume-item pb-0">
              <h4>Muhammad Erdiansyah</h4>
              <p class="text-dark">
                <em
                  >Diligent computer engineering student (GPA 4.0) from Sultan Syarif Kasim Riau State Islamic University with research and proven skills competence. Internship at PT Dicoding where I was given experience on how to work well
                  in develop programming techniques. Looking for a suitable position my qualifications to expand my sharpness knowledge and experience in programming field.</em
                >
              </p>
              <ul class="text-dark">
                <li>Pekanbaru, Riau, Indonesia</li>
                <li>+6285161312203</li>
                <li>ianmuhammad27@gmail.com</li>
              </ul>
            </div>

            <h3 class="resume-title">Education</h3>
            <div class="resume-item">
              <h4>Bachelor Degree Informatic Program</h4>
              <h5 class="text-dark">2020 – 2024</h5>
              <p class="text-dark"><em>Sultan Syarif Kasim State Islamic University Riau</em></p>
              <p class="text-dark">I was the best graduate in our class and according to my major with a 4.00 GPA.</p>
            </div>
            <div class="resume-item">
              <h4>High School Graduate</h4>
              <h5 class="text-dark">2017 – 2020</h5>
              <p class="text-dark"><em>Vacational High School 2 Pekanbaru</em></p>
              <p class="text-dark">Received a Certificate of Competence from a Indonesian Professional Certification Authority in area of : Inspector Power Amplifier Electric Check.</p>
            </div>
          </div>
          <div class="col-lg-6">
            <h3 class="resume-title">Organization Experience</h3>
            <div class="resume-item">
              <h4>Head of HID netsquad suska department</h4>
              <h5 class="text-dark">2021 - Present</h5>
              <p class="text-dark"><em>Sultan Syarif Kasim State Islamic University Riau</em></p>
              <ul class="text-dark">
                <li>Lead in the design, development, and implementation of the graphic, layout, and production communication materials</li>
                <li>Delegate tasks to the 7 members of the design team and provide counsel on all aspects of the project.</li>
                <li>Supervise the assessment of all graphic materials in order to ensure quality and accuracy of the design</li>
                <li>Oversee the efficient use of production project budgets ranging from $500 - $10,000</li>
              </ul>
            </div>
            <div class="resume-item">
              <h4>HID Simatif</h4>
              <h5 class="text-dark">2020 - 2021</h5>
              <p class="text-dark"><em>Sultan Syarif Kasim State Islamic University Riau</em></p>
              <ul class="text-dark">
                <li>Developed numerous marketing programs (logos, flyers, infographics, videos, and banners).</li>
                <li>Managed up to 5 project design or tasks at a given time while under pressure</li>
                <li>Recommended and consulted with expert team on the most appropriate graphic design</li>
                <li>Created 4+ design presentations and logos philosophy of SIMATIF</li>
                <li>Short video thank you SIMATIF 2021, see you in SIMATIF 2022</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- End Resume Section -->
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
    <p>Page Resume <a href="https://www.instagram.com/mhderdnsyh/" class="text-white fw-bold">mhderdnsyh</a></p>
  </footer>
  <!-- Akhir Footer -->
</template>

<script>
export default {};
</script>

<style>
/*--------------------------------------------------------------
# General
--------------------------------------------------------------*/
body {
  font-family: "Open Sans", sans-serif;
  color: #272829;
}

a {
  color: #0563bb;
  text-decoration: none;
}

a:hover {
  color: #067ded;
  text-decoration: none;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: "Raleway", sans-serif;
}
/*--------------------------------------------------------------
# Resume
--------------------------------------------------------------*/
.resume {
  margin-top: 35px;
  margin-left: 9%;
}
.resume .resume-title {
  font-size: 26px;
  font-weight: 700;
  margin-top: 20px;
  margin-bottom: 20px;
  padding: 10px;
  color: #45505b;
}
.resume .resume-item {
  padding: 0 0 20px 20px;
  margin-top: -2px;
  margin-left: 10px;
  border-left: 2px solid #728394;
  position: relative;
}
.resume .resume-item h4 {
  line-height: 18px;
  font-size: 18px;
  font-weight: 600;
  text-transform: uppercase;
  font-family: "Poppins", sans-serif;
  color: #728394;
  margin-bottom: 10px;
}
.resume .resume-item h5 {
  font-size: 16px;
  background: #f7f8f9;
  padding: 5px 15px;
  display: inline-block;
  font-weight: 600;
  margin-bottom: 10px;
}
.resume .resume-item ul {
  padding-left: 20px;
}
.resume .resume-item ul li {
  padding-bottom: 10px;
  padding-right: 20px;
}
.resume .resume-item:last-child {
  padding-bottom: 0;
}
.resume .resume-item::before {
  content: "";
  position: absolute;
  width: 16px;
  height: 16px;
  border-radius: 50px;
  left: -9px;
  top: 0;
  background: #fff;
  border: 2px solid #728394;
}
body {
  text-align: justify;
}
footer {
  margin-top: -6%;
  position: relative;
}
</style>
