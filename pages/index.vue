<template>
  <div>
    <link
      href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css"
      rel="stylesheet"
    />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,200;0,300;0,400;0,500;1,200&display=swap"
      rel="stylesheet"
    />
    <Navbar />

    <section id="hero">
      <img src="~/assets/img/hero-image.png" class="hero-img" alt="" />
      <div class="hero-title">
        Jadi bagian dari perjalanan kami untuk menjadi penggerak <br />
        perkembangan teknologi di industri konstruksi di
        <span style="color: #f67d20">Indonesia!</span>
      </div>
      <div class="hero-tag">
        <span style="color: #828282">Cari pekerjaan yang Kamu inginkan</span>
      </div>
      <div class="hero-search" align="center">
        <div class="input-group mb-3">
          <input
            type="text"
            class="form-control hero-input"
            placeholder="UI/UX Designer, Web Developer, dll."
            aria-label="UI/UX Designer, Web Developer, dll."
            aria-describedby="basic-addon2"
          />
          <button class="btn hero-button">
            <i class="bx bx-search-alt-2"></i> Cari
          </button>
        </div>
      </div>
    </section>

    <section id="content">
      <div class="container-fluid">
        <div class="row">
          <div class="col-md-6">
            <div class="content-img">
              <img
                src="~/assets/img/yt.png"
                class="img-fluid content-img"
                alt="Content"
                srcset=""
              />
              <button class="btn btn-play">
                <img src="~/assets/img/Next.svg" alt="" />
              </button>
            </div>
          </div>
          <div class="col-md-6">
            <div class="content-title">
              Seperti apa bekerja di
              <span style="color: #f67d20">GoCement?</span>
            </div>
            <p>
              Kami percaya sebuah perubahan harus dimulai dengan sebuah tekad
              dan keyakinan. Oleh karena itu, kita perlu mengerahkan kepala,
              tangan, dan hati secara 100%. Strategi dan eksekusi sangatlah
              penting, namun diatas semuanya, perlu motivasi dan tekad yang
              berasal dari dalam hati. Inilah yang kami lakukan untuk menghadapi
              setiap tantangan di industri konstruksi yang memiliki perubahan
              cepat dan menjadikan kami dapat berpikir untuk memecahkan masalah
              dengan cara yang kreatif.
            </p>
          </div>
        </div>
      </div>
    </section>

    <section id="about">
      <div class="container-fluid">
        <img src="~/assets/img/Photo.png" class="img-fluid img-about" alt="" />

        <div class="card card-about">
          <div class="card-body">
            <div class="row" align="center">
              <div class="col-md-3 mb-3">
                <h3>11rb+</h3>
                <span>Unduhan</span>
              </div>
              <div class="col-md-3">
                <h3>4.9</h3>
                <span>Bintang di Playstore</span>
              </div>
              <div class="col-md-3">
                <h3>100+</h3>
                <span>Karyawan</span>
              </div>
              <div class="col-md-3">
                <h3>10+</h3>
                <span>Divisi Perusahaan</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="perks">
      <div class="container-fluid">
        <div class="row">
          <div class="col-md-5">
            <img src="~/assets/img/perks-img.png" class="img-fluid" alt="" />
          </div>
          <div class="col-md-7">
            <div class="perks-title">
              Culture & Value Go<span style="color: #f67d20">Cement</span>
              <div class="row">
                <div class="col-sm-6">
                  <div class="perks-badge">
                    <div class="hug">
                      <h4>F</h4>
                    </div>
                    <h4 class="mt-5">Friendly</h4>
                    We are not just colleagues, we are community.
                    <span class="text-muted"
                      >Kami bahu membahu untuk mendengar satu dengan yang lain
                      dan membangun lingkungan kerja yang menyenangkan!</span
                    >
                  </div>
                </div>
                <div class="col-sm-6">
                  <div class="perks-badge">
                    <div class="hug">
                      <h4>A</h4>
                    </div>
                    <h4 class="mt-5">Active</h4>
                    <span class="text-muted"
                      >Dalam bekerja, kami sangat menghargai semangat untuk
                      selalu aktif dan memiliki inisiatif. </span
                    >Transformasi akan terjadi apabila adanya keinginan untuk
                    berkembang!
                  </div>
                </div>
              </div>
              <div class="row">
                <div class="col-sm-6">
                  <div class="perks-badge">
                    <div class="hug">
                      <h4>S</h4>
                    </div>
                    <h4 class="mt-5">Smart</h4>
                    Pembelajaran adalah proses seumur hidup. Setiap hari, kami
                    diajarkan untuk memiliki kemauan untuk
                    <span class="text-muted"
                      >belajar seperti seorang pembelajar dan memecahkan masalah
                      secara cerdas.</span
                    >
                  </div>
                </div>
                <div class="col-sm-6">
                  <div class="perks-badge">
                    <div class="hug">
                      <h4>T</h4>
                    </div>
                    <h4 class="mt-5">Trusted</h4>
                    Trust is granted, not earned.
                    <span class="text-muted"
                      >Kami berkomitmen untuk selalu memiliki empati dan
                      integritas, serta menjadi autentik dalam segala sesuatu
                      yang kami kerjakan.</span
                    >
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="jelajah">
      <div class="container-fluid">
        <div class="jelajah-title">
          Jelajahi posisi di Go<span style="color: #f67d20">Cement</span>
        </div>
        <div class="row mt-5 jelajah-icons">
          <div class="col-md-3 mb-4" align="center">
            <img src="~/assets/img/ab-1.png" class="img-fluid" alt="" /><br />
            <span class="mt-2"><u>Engineer</u></span>
          </div>
          <div class="col-md-3 mb-4" align="center">
            <img
              src="~/assets/img/ab-2.png"
              class="img-fluid"
              alt=""
            /><br /><br />
            <span class="mt-2"><u>Design & Product</u></span>
          </div>
          <div class="col-md-3 mb-4" align="center">
            <img
              src="~/assets/img/ab-3.png"
              class="img-fluid"
              alt=""
            /><br /><br />
            <span class="mt-2"><u>Marketing & Creative</u></span>
          </div>
          <div class="col-md-3 mb-4" align="center">
            <img
              src="~/assets/img/ab-4.png"
              class="img-fluid"
              alt=""
            /><br /><br />
            <span class="mt-2"><u>Data & Analytics</u></span>
          </div>
        </div>
        <div class="row mt-5 jelajah-icons">
          <div class="col-md-3 mb-4" align="center">
            <img
              src="~/assets/img/ab-5.png"
              class="img-fluid"
              alt=""
            /><br /><br />
            <span class="mt-2"><u>Finance</u></span>
          </div>
          <div class="col-md-3 mb-4" align="center">
            <img
              src="~/assets/img/ab-6.png"
              class="img-fluid"
              alt=""
            /><br /><br />
            <span class="mt-2"><u>People & Culture</u></span>
          </div>
          <div class="col-md-3 mb-4" align="center">
            <img
              src="~/assets/img/ab-7.png"
              class="img-fluid"
              alt=""
            /><br /><br />
            <span class="mt-2"><u>Revanue</u></span>
          </div>
          <div class="col-md-3 mb-4" align="center">
            <img
              src="~/assets/img/ab-8.png"
              class="img-fluid"
              alt=""
            /><br /><br />
            <span class="mt-2"><u>Information Security</u></span>
          </div>
        </div>
      </div>
    </section>

    <section id="artikel">
      <div class="artikel-title">
        Artikel Terbaru
        <nuxt-link
          to="/"
          style="
            color: #f67d20;
            font-size: 14px;
            text-decoration: underline;
            font-weight: 500;
          "
          >Lihat semua artikel (37)</nuxt-link
        >
      </div>

      <div class="artikel-card">
        <div class="row mt-5">
          <div class="col-md-3 mb-3">
            <div class="card">
              <img src="~/assets/img/ar-1.png" class="card-img-top" alt="" />
              <div class="card-body">
                <h5 class="card-title">
                  Kelebihan Pembangunan dengan Konstruksi Baja
                </h5>
                <p class="card-text text-muted">
                  Penggunaan aplikasi konstruksi baja memiliki banyak kelebihan
                  dibandingkan beton atau bahan kayu. bahan kayu. bahan kayu.
                </p>

                <div class="row">
                  <div class="col-sm-3">
                    <img src="~/assets/img/ar-p.png" class="img-fluid" alt="" />
                  </div>
                  <div class="col-sm-9">
                    <span
                      style="color: #f67d20; font-size: 16px; font-weight: 500"
                      >Grifani Akmala</span
                    ><br />
                    <small
                      class="text-muted"
                      style="font-weight: 400; font-size: 14px"
                      >7 November 2022</small
                    >
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-3 mb-3">
            <div class="card">
              <img src="~/assets/img/ar-2.png" class="card-img-top" alt="" />
              <div class="card-body">
                <h5 class="card-title">
                  Mengenal Tentang Konstruksi Baja Modern
                </h5>
                <p class="card-text text-muted">
                  Konstruksi baja banyak di gunakan dalam aplikasi sebagai tiang
                  bangunan, rangka jembatan, rangka bangunan dan lain-lain.
                </p>

                <div class="row">
                  <div class="col-sm-3">
                    <img src="~/assets/img/ar-p.png" class="img-fluid" alt="" />
                  </div>
                  <div class="col-sm-9">
                    <span
                      style="color: #f67d20; font-size: 16px; font-weight: 500"
                      >Grifani Akmala</span
                    ><br />
                    <small
                      class="text-muted"
                      style="font-weight: 400; font-size: 14px"
                      >7 November 2022</small
                    >
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-3 mb-3">
            <div class="card">
              <img src="~/assets/img/ar-3.png" class="card-img-top" alt="" />
              <div class="card-body">
                <h5 class="card-title">
                  Elemen Utama Struktur konstruksi Bangunan
                </h5>
                <p class="card-text text-muted">
                  Dalam pembangunan sebuah konstruksi, ada bagian-bagian elemen
                  serta memilki fungsi tersendiri. tersendiri. tersendiri.
                  tersendiri.
                </p>

                <div class="row">
                  <div class="col-sm-3">
                    <img src="~/assets/img/ar-p.png" class="img-fluid" alt="" />
                  </div>
                  <div class="col-sm-9">
                    <span
                      style="color: #f67d20; font-size: 16px; font-weight: 500"
                      >Grifani Akmala</span
                    ><br />
                    <small
                      class="text-muted"
                      style="font-weight: 400; font-size: 14px"
                      >7 November 2022</small
                    >
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-3 mb-3">
            <div class="card">
              <img src="~/assets/img/ar-4.png" class="card-img-top" alt="" />
              <div class="card-body">
                <h5 class="card-title">
                  Analisa Kerangka Tembok Rumah Berbahan Kayu dan Baja Ringan
                </h5>
                <p class="card-text text-muted">
                  Rangka bangunan merupakan struktur pendukung utama yang perlu
                  diperhatikan apabila anda hendak ...
                </p>

                <div class="row">
                  <div class="col-sm-3">
                    <img src="~/assets/img/ar-p.png" class="img-fluid" alt="" />
                  </div>
                  <div class="col-sm-9">
                    <span
                      style="color: #f67d20; font-size: 16px; font-weight: 500"
                      >Grifani Akmala</span
                    ><br />
                    <small
                      class="text-muted"
                      style="font-weight: 400; font-size: 14px"
                      >7 November 2022</small
                    >
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="tagline" align="center">
      <div class="tagline-title">
        Pakai Go<span style="color: #f67d20">Cement</span> #PastiBeres
      </div>
      <button class="btn btn-tagline">
        Bergabung bersama kami <i class="bx bx-chevron-right"></i>
      </button>
    </section>

    <section id="footer">
      <div class="footer-1">
        <div class="container-fluid">
          <div class="row">
            <div class="col-md-6">
              <div class="row">
                <div class="col-sm-3">
                  <img src="~/assets/img/logo-2.png" class="img-fluid" alt="" />
                </div>
                <div class="col-sm-9">
                  <span
                    style="color: #f67d20; font-weight: 600; font-size: 16px"
                    >Gocement</span
                  >
                  <p class="text-muted">
                    GoCement adalah B2B marketplace bahan bangunan terdepan di
                    Indonesia. Bandingkan dan dapatkan biaya paling terjangkau
                    sampai ke lokasi proyek. Dengan GoCement #PastiBeres.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-md-6" align="center">
              <span style="color: #f67d20; font-weight: 600; font-size: 16px"
                >Download Aplikasi</span
              ><br /><br />
              <img src="~/assets/img/playstore.png" class="img-fluid" alt="" />
            </div>
          </div>
        </div>
      </div>
      <div class="footer-2">
        <div class="container-">
          <div class="row">
            <div class="col-md-4">
              <span style="color: #f67d20; font-weight: 600; font-size: 16px"
                >Customer Service</span
              >
              <p>
                Senin - Jumat: 09:00 - 22:00 WIB <br />
                Sabtu: 09:00 - 21:00 WIB <br />
                Minggu: 10:00 - 18:00 WIB <br /><br />

                <i class="bx bxs-phone" style="color: #f67d20"></i> 031 -
                19191929 <br />
                <i class="bx bx-envelope" style="color: #f67d20"></i>
                support@email.com
              </p>
            </div>
            <div class="col-md-4">
              <span style="color: #f67d20; font-weight: 600; font-size: 16px"
                >Ikuti kami di:</span
              >
              <div class="row mt-3 icon-footer">
                <div class="col-sm-3">
                  <i
                    class="bx bxl-instagram"
                    style="color: #f67d20; font-size: 27px"
                  ></i>
                </div>
                <div class="col-sm-3">
                  <i
                    class="bx bxl-facebook-square"
                    style="color: #f67d20; font-size: 27px"
                  ></i>
                </div>
                <div class="col-sm-3">
                  <i
                    class="bx bxl-youtube"
                    style="color: #f67d20; font-size: 27px"
                  ></i>
                </div>
                <div class="col-sm-3">
                  <i
                    class="bx bxl-twitter"
                    style="color: #f67d20; font-size: 27px"
                  ></i>
                </div>
                <br />
                <span class="ml-3 mt-4">blog.gocement.com</span>
              </div>
            </div>
            <div class="col-md-4">
              <span style="color: #f67d20; font-weight: 600; font-size: 16px"
                >Metode Pembayaran</span
              >
              <div class="row">
                <div class="col">
                  <img
                    src="~/assets/img/i-bca.png"
                    style="width: 100px"
                    class="img-fluid"
                    alt=""
                  />
                </div>
                <div class="col">
                  <img
                    src="~/assets/img/i-mandiri.png"
                    style="width: 100px"
                    class="img-fluid"
                    alt=""
                  />
                </div>
                <div class="col">
                  <img
                    src="~/assets/img/i-permata.png"
                    style="width: 100px"
                    class="img-fluid"
                    alt=""
                  />
                </div>
                <div class="col">
                  <img
                    src="~/assets/img/i-sampoerna.png"
                    style="width: 100px"
                    class="img-fluid"
                    alt=""
                  />
                </div>
                <div class="col">
                  <img
                    src="~/assets/img/i-bri.png"
                    style="width: 100px"
                    class="img-fluid"
                    alt=""
                  />
                </div>
              </div>
              <div class="row mt-2">
                <div class="col">
                  <img
                    src="~/assets/img/i-bsi.png"
                    style="width: 100px"
                    class="img-fluid"
                    alt=""
                  />
                </div>
                <div class="col">
                  <img
                    src="~/assets/img/i-bjb.png"
                    style="width: 100px"
                    class="img-fluid"
                    alt=""
                  />
                </div>
                <div class="col">
                  <img src="~/assets/img/i-alfa.png" class="img-fluid" alt="" />
                </div>
                <div class="col">
                  <img src="~/assets/img/i-midi.png" class="img-fluid" alt="" />
                </div>
                <div class="col">
                  <img
                    src="~/assets/img/i-dandan.png"
                    class="img-fluid"
                    alt=""
                  />
                </div>
              </div><br><br>

              <span style="color: #f67d20; font-weight: 600; font-size: 16px"
                >Kontak
              </span><br><br>
              <button class="btn btn-kontak">
                <i class='bx bxl-whatsapp-square' ></i> Hubungi WhatsApp kami
              </button>
            </div>
          </div>
        </div>
      </div>
      <div class="footer-3" align="center">
        © 2021- 2022, PT. Mitra Semen Asia @ www.gocement.com
      </div>
    </section>
  </div>
</template>

<script src="https://unpkg.com/boxicons@2.1.4/dist/boxicons.js"></script>
<script>
import Navbar from "~/components/Navbar.vue";

export default {
  name: "IndexPage",
  components: {
    Navbar,
  },
};
</script>

<style>
/* start hero section */
#hero .hero-img {
  position: absolute;
  width: 100%;
  height: 410px;
}
#hero .hero-title {
  position: relative;
  font-family: "Poppins", sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 34px;
  line-height: 150%;
  text-align: center;
  top: 70px;
}
@media (max-width: 768px) {
  #hero .hero-title {
    font-size: 15px;
  }
  #hero .hero-img {
    width: 100%;
    height: 100%;
  }
}
@media (max-width: 980px) {
  #hero .hero-img {
    width: 100%;
    height: 25%;
  }
  #hero .hero-title {
    font-size: 15px;
    top: 20px;
  }
}
#hero .hero-tag {
  position: relative;
  font-family: "Poppins", sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 20px;
  line-height: 100%;
  text-align: center;
  top: 100px;
}
@media (max-width: 768px) {
  #hero .hero-tag {
    font-size: 16px;
    top: 100px;
  }
}
@media (max-width: 980px) {
  #hero .hero-tag {
    font-size: 14px;
    top: 40px;
  }
}
#hero .hero-search {
  padding-top: 130px;
  padding-left: 500px;
  padding-right: 500px;
}
@media (max-width: 768px) {
  #hero .hero-search {
    padding-top: 100px;
    padding-left: 90px;
    padding-right: 90px;
  }
}
@media (max-width: 980px) {
  #hero .hero-search {
    padding-top: 60px;
    padding-left: 90px;
    padding-right: 90px;
  }
}
#hero .hero-search .hero-input {
  height: 50px;
}
@media (max-width: 768px) {
  #hero .hero-search .hero-input {
    height: 40px;
  }
}
@media (max-width: 980px) {
  #hero .hero-search .hero-input {
    height: 40px;
  }
}
#hero .hero-search .hero-button {
  background: #f67d20;
  color: white;
  border-radius: 0px 4px 4px 0px;
}
@media (max-width: 768px) {
  #hero .hero-search .hero-button {
    height: 20px;
  }
}
@media (max-width: 980px) {
  #hero .hero-search .hero-button {
    height: 40px;
  }
}
/* end section hero */

/* Start content section */
#content {
  margin-top: 200px;
  margin-bottom: 200px;
  padding-left: 50px;
}
@media (max-width: 768px) {
  #content {
    margin-top: 100px;
    margin-bottom: 100px;
    padding-left: 20px;
  }
}
@media (max-width: 980px) {
  #content {
    margin-top: 100px;
    margin-bottom: 100px;
    padding-left: 20px;
  }
}
#content .content-img {
  border-radius: 10px;
  background-size: cover;
}
#content .content-img .btn-play {
  border-radius: 50%;
  display: block;
  position: absolute;
  left: calc(40% - 47px);
  top: calc(50% - 47px);
  overflow: hidden;
}
#content .content-title {
  font-family: "Poppins", sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 34px;
  line-height: 150%;
  padding-right: 110px;
  padding-top: 50px;
}
@media (max-width: 768px) {
  #content .content-title {
    font-size: 20px;
    padding-right: 0px;
  }
}
@media (max-width: 980px) {
  #content .content-title {
    font-size: 20px;
    padding-right: 0px;
  }
}
#content p {
  font-family: "Poppins", sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 150%;
  padding-right: 110px;
  padding-top: 20px;
  color: #828282;
}
@media (max-width: 768px) {
  #content p {
    font-size: 14px;
    padding-right: 0px;
  }
}
@media (max-width: 980px) {
  #content p {
    font-size: 14px;
    padding-right: 0px;
  }
}
/* end content section */

/* start about section */
#about {
  /* margin-top: 100px; */
  margin-bottom: 150px;
  padding-left: 50px;
  padding-right: 50px;
}
#about .img-about {
  width: 100%;
}
@media (max-width: 768px) {
  #about {
    margin-bottom: 100px;
    /* padding-left: 20px;
    padding-right: 20px; */
  }
  #about .img-about {
    width: 100%;
  }
}
@media (max-width: 980px) {
  #about {
    margin-bottom: 100px;
    padding-left: 20px;
    margin-left: 200px;
  }
  #about .img-about {
    width: 100%;
  }
}
#about .card-about {
  margin-top: 100px;
  background: #f67d20;
  color: white;
  border: none;
  border-radius: 0;
}
@media (max-width: 768px) {
  #about .card-about {
    margin-top: 100px;
  }
}
@media (max-width: 980px) {
  #about .card-about {
    margin-left: -208px;
    margin-top: 400px;
    margin-right: -40px;
    padding: 20px;
  }
}
/* end about section */

/* start perks section */
#perks {
  margin-top: 100px;
  margin-bottom: 150px;
  padding-left: 50px;
  padding-right: 50px;
}
#perks .perks-title {
  font-family: "Poppins", sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 100%;
}
#perks .hug {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 10px;
  padding-top: 5;
  width: 48px;
  height: 48px;
  background: #fff2e9;
  border-radius: 6px;
  color: #f67d20;
  margin-top: 30px;
}
#perks .perks-badge h4 {
  font-family: "Poppins", sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 20px;
  line-height: 100%;
  margin-top: 10px;
}
#perks .perks-badge {
  font-family: "Poppins", sans-serif;
  font-style: normal;
  font-weight: 400;
  font-size: 12px;
  line-height: 100%;
  margin-top: 10px;
}
/* end perks section */

/* start jelajah section */
#jelajah .jelajah-title {
  font-family: "Poppins", sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 100%;
  text-align: center;
}
#jelajah .jelajah-icons {
  padding-top: 100px;
  padding-left: 300px;
  padding-right: 300px;
}
@media (max-width: 768px) {
  #jelajah .jelajah-icons {
    padding-left: 20px;
    padding-right: 20px;
  }
}
@media (max-width: 980px) {
  #jelajah .jelajah-icons {
    padding-left: 20px;
    padding-right: 20px;
  }
}
/* end jelajah section  */

/* start artikel section */
#artikel {
  margin-top: 100px;
  margin-bottom: 100px;
  padding-left: 50px;
  padding-right: 50px;
}
#artikel .artikel-title {
  font-family: "Poppins", sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 100%;
}
/* end artikel section */

/* start tagline section */
#tagline .tagline-title {
  font-family: "Poppins", sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 100%;
  text-align: center;
}
#tagline .btn-tagline {
  background: #f67d20;
  border-radius: 4px;
  border: none;
  color: white;
  margin-top: 30px;
}

.btn-tagline:hover {
  background: transparent;
  border-radius: 4px;
  color: #f67d20;
  border: 2px solid #f67d20;
}
/* end tagline saction */

/* start footer section  */
#footer {
  margin-top: 100px;
}
#footer .footer-1 {
  border: 1px solid rgb(215, 215, 215);
  padding: 20px;
}
#footer .footer-2 {
  border: 1px solid rgb(215, 215, 215);
  padding: 40px;
}
#footer .footer-2 .icon-footer {
  padding-right: 300px;
}
@media (max-width: 768px) {
  #footer .footer-2 .icon-footer {
    padding-right: 0px;
  }
}
@media (max-width: 980px) {
  #footer .footer-2 .icon-footer {
    padding-right: 0px;
  }
}
#footer .btn-kontak {
  background: #f67d20;
  border-radius: 4px;
  border: none;
  color: white;
}

.btn-kontak:hover {
  background: transparent;
  border-radius: 4px;
  color: #f67d20;
  border: 2px solid #f67d20;
}

#footer .footer-3 {
  background: #f67d20;
  color: white;
  padding: 30px;
}
/* end footer section */
</style>
