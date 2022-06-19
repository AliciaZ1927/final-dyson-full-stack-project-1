<template>
  <section id="top" class="second section">
    <div class="banner">
      <video autoplay muted loop>
        <source src="../assets/d-4.mp4" type="video/mp4" />
      </video>
    </div>
    <div class="container">
      <div class="text-center justbuy">
        <span class="m-3 px-4 py-2 text-light"> Welcome to Dyson </span>
        <!-- <br /> -->
        <!-- <div class="d-flex justify-content-center">
          <div class="btn btn-light p-1 mx-3">頭髮護理</div>
          <div class="btn btn-light p-1 mx-3">空氣清淨機</div>
          <div class="btn btn-light p-1 mx-3">吸塵器</div>
        </div> -->
      </div>
    </div>
  </section>
  <section class="third section">
    <div class="container-fluid">
      <div class="row">
        <div class="col-md-6">
          <div class="m-5">
            <div class="card-body">
              <div class="text-center card-body">
                <img
                  src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgL3zUscrIWRCRXksoQoxb7MGcjlKwAoXZQkAAxwYwU_lGIXsbGAw5sixqETpQEz6scFM0pJUq15p9vJLRZs1rMNiaDYsQDfASA3uNKHvH9Vh0OLbGWOxjA9ydwTx2kXEDPdJZFmvpQb4KTen-j1jEJQBu9n5IECadq_7rwuyOOGYMH6bX1E0Lzn_hHeg/s320/d1.webp"
                  class="card-img-top"
                  alt="..."
                />

                <h5 class="title text-light mt-5 m-3">
                  新一代 Dyson V11™ Fluffy+ 無線吸塵器
                </h5>
                <router-link
                  class="nav-link link-light"
                  to="/VacuumCleaner"
                  @click="tabChange(VacuumCleaner)"
                  ><a class="p-2 btn btn-secondary">去逛逛</a></router-link
                >
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-6">
          <div class="m-5">
            <div class="card-body">
              <div class="text-center card-body">
                <img
                  src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEj0EOA5sp9TgiKo7XlRmkEz_J85b0Oqd1904tl8WjaaFm-JhqrEoRIGiZfGM1Nj7ZaAiXGP3VmPq_jBk4Q_mzZegk0WQ-JjYK_D-2_h_TIgRDaQ_gQd4ASXI272Ar-_61-8Uwi7Qhq9cuZBIdKg2YK4jjuOEo8fZW82slaY5kycxH-A3R-TFxjOH_1Y3w/s320/d-3.jpg"
                  class="card-img-top"
                  alt="..."
                />

                <h5 class="title text-light mt-5 m-3">
                  全新色彩工藝完美妝點 Dyson Supersonic 吹風機普魯士藍冬日限定版
                </h5>
                <router-link class="nav-link link-light" to="/hair"
                  ><a class="p-2 btn btn-secondary">去逛逛</a></router-link
                >
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-6">
          <div class="m-5">
            <div class="card-body">
              <div class="text-center card-body">
                <img
                  src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEi3jgfa08mw6nqDQbaa53UyiGID2NQa7_uzraq9wdJAk1q8FLusW09h0Afmi8YeXrRTzqdaHSNJw29l0mdS-OjCR6_8B7iv0jWsVAkuTfKO3kZRGhCs53jAZsZWuAvDcGC7ChTORlasuzEYGz2XpykIjsMKpfRm_zmmkMy1AYnOc5J501dLpWP8xmuv5w/s320/11.webp"
                  class="card-img-top"
                  alt="..."
                />

                <h5 class="title text-light mt-5 m-3">
                  Dyson Pure Cool Cryptomic™ 二合一涼風智慧空氣清淨機
                </h5>
                <router-link
                  class="nav-link link-light"
                  to="/airpurifier"
                  @click="tabChange(AirPurifier)"
                  ><a class="p-2 btn btn-secondary">去逛逛</a></router-link
                >
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-6">
          <div class="m-5">
            <div class="card-body">
              <div class="text-center card-body">
                <img
                  src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEha14MXkpAvIELyc700yFBzZXnP91xW-zCAgERGahOp7pLsP_HmdkDtAX893JhWox_xYWQXyrP1b7335KLAPHdyKh6dr2CLIa2s06jP7PzKhQPGewU-xwLI0HFacaLm0vwcJY_K2FznhPncvUL9PwGo3QKXTIhLWe7-JpRy065TVbYavynfdRGLUNFjoQ/s320/12.webp"
                  class="card-img-top"
                  alt="..."
                />

                <h5 class="title text-light mt-5 m-3">
                  Dyson Corrale™ 直捲髮造型器 桃紅色
                </h5>
                <router-link class="nav-link link-light" to="/hair"
                  ><a class="p-2 btn btn-secondary">去逛逛</a></router-link
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section class="four section">
    <div class="picture">
      <div class="inner">
        「我們身為設計工程師，其實和很多人一樣，經常對不好用的產品感到失望，因此全心全意創新及不斷改良，努力解決這些日常生活中的問題。」
      </div>
    </div>
  </section>
  <section class="five section">
    <div class="banner">
      <video autoplay muted loop>
        <source src="../assets/d1.mp4" type="video/mp4" />
      </video>
    </div>
  </section>
  <section class="six section">
    <div
      id="carouselExampleControls"
      class="carousel slide"
      data-bs-ride="carousel"
    >
      <div class="carousel-inner">
        <div class="carousel-item active">
          <div id="innertext" class="carousel-caption d-none d-md-block">
            <h3>嶄新創意</h3>
            <p class="mt-3">
              1978年，James
              Dyson因吸塵器的吸力日漸減弱而感到困擾。他將吸塵器拆開，發現塵垢堵塞集塵袋，導致吸力下降。那時候，他剛剛為工廠增建了一個工業用氣旋塔，以離心力將油漆微粒從空氣中分離。他開始思考，同樣的原理可不可以用於吸塵器呢？
              <br />
              自此，他開始研究工作，測試了5,127個試驗原型後，終於發明出全球首部無集塵袋吸塵器。
            </p>
          </div>
          <img
            src="https://www.dyson.tw/medialibrary/Group/Carousels/SlideBackground/NonProductPages/AllMarkets/AboutDyson/AboutDyson_ANewIdea_1000x560.ashx?h=560&la=zh-TW&w=1000&hash=A647F9E7FC141599E2326F5D74999FD6"
            class="d-block w-100"
          />
        </div>
        <div class="carousel-item">
          <div id="innertext" class="carousel-caption d-none d-md-block">
            <h3>離心力</h3>
            <p class="mt-3">
              James
              Dyson的新型吸塵器初期在科技大國日本發售。它的離心力令日本人趨之若鶩，而卓越的吸塵效能更迅速奠定市場地位。那時候，每部售價為2,000美元。1991年，Dyson也在日本國際設計展贏得獎項。
            </p>
          </div>
          <img
            src="https://www.dyson.tw/medialibrary/Group/Carousels/SlideBackground/NonProductPages/AllMarkets/AboutDyson/AboutDyson_GForce_1000x560.ashx?h=563&la=zh-TW&w=1000&hash=D2F0109DA18359C033E14DBE7B2ADE12"
            class="d-block w-100"
          />
        </div>
        <div class="carousel-item">
          <div id="innertext" class="carousel-caption d-none d-md-block">
            <h3>DC01</h3>
            <p class="mt-3">
              離心力所帶來的利潤，讓James Dyson可以開辦自己的公司－－Dyson
              Ltd.。1993年，他在Cotswolds成立自己的研究中心及廠房，致力研發新一代吸塵器，目標是吸除更細小的塵埃微粒。這部運用雙氣旋的DC01，是當時第一款由始至終維持100%吸力的吸塵器。
            </p>
          </div>
          <img
            src="https://www.dyson.tw/medialibrary/Group/Carousels/SlideBackground/NonProductPages/AllMarkets/AboutDyson/AboutDyson_DC01_1000x560.ashx?h=560&la=zh-TW&w=1000&hash=B35698D798AF912001CC76CAA3D6E508"
            class="d-block w-100"
          />
        </div>
      </div>
      <button
        class="carousel-control-prev"
        type="button"
        data-bs-target="#carouselExampleControls"
        data-bs-slide="prev"
      >
        <i class="fa-solid fa-circle-chevron-left"></i>
        <!-- <span class="carousel-control-prev-icon" aria-hidden="true"></span> -->
        <!-- <span class="visually-hidden">Previous</span> -->
      </button>
      <button
        class="carousel-control-next"
        type="button"
        data-bs-target="#carouselExampleControls"
        data-bs-slide="next"
      >
        <i class="fa-solid fa-circle-chevron-right"></i>
        <!-- <span class="carousel-control-next-icon" aria-hidden="true"></span> -->
        <!-- <span class="visually-hidden">Next</span> -->
      </button>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
* {
  padding: 0;
  margin: 0;
  list-style: none;
}
section .banner {
  width: 100%;
  height: 100vh;
  position: relative;
}
section.second video {
  /* top: -300; */
  position: absolute;
  width: 100%;
  object-fit: cover;
  height: 100vh;
  /* background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
    url(https://picsum.photos/600/300?random=8); */
  /* background-size: 100vw 100vh; */
  background-size: contain;
  background-repeat: no-repeat;
}
section span {
  font-size:60px;
  background-color: #161616af;
  font-family: 'Caveat', cursive;
  border-radius:50px;
}
section div .justbuy {
  font-size: 2.5rem;
  position: absolute;
  bottom: 100px;
  text-align: center;
  /* margin-left: auto;
    margin-right: auto; */
  left: 0;
  right: 0;
  list-style: none;
}
section div .justbuy a:hover {
  color: #ac8776;
}
section.third {
  height: 100%;
  background-color: #161616;
}
@media screen and (max-width: 1440px) {
  section.third {
    height: 200%;
    background-color: #161616;
  }
  /* section.four .inner {
    padding-top: 100px;
    margin-left: 150px;
    width: 300px;
    height: 600px;
    font-size: 1.5rem;
  } */
}
section.third .card {
  border-color: #161616;
  border-radius: 20px;
}
section.third img {
  border-radius: 10px;
  width: 600px;
  height: 420px;
}
section.four .picture {
  height: 100vh;
  background-image: linear-gradient(
      rgba(255, 255, 255, 0.005),
      rgba(255, 255, 255, 0)
    ),
    url(https://www.dyson.tw/medialibrary/Group/Carousels/SlideBackground/NonProductPages/AllMarkets/AboutDyson/AboutDyson_Intro_JamesDyson_1000x560.ashx?h=560&la=zh-TW&w=1000&hash=E7FFDC7B56D32EB7C345E0D6EEC82058);
  background-size: 100vw 100vh;
  background-repeat: no-repeat;
}
section.four .inner {
  padding-top: 100px;
  margin-left: 150px;
  width: 600px;
  height: 600px;
  font-weight: bold;
  font-size: 2rem;
}
@media screen and (max-width: 780px) {
  section.four .inner {
    padding-top: 50px;
    margin-left: 100px;
    width: 300px;
    height: 600px;
    font-size: 1.5rem;
  }
}
section.five video {
  /* top: -300; */
  position: absolute;
  width: 100%;
  object-fit: cover;
  height: 100vh;
  /* background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
    url(https://picsum.photos/600/300?random=8); */
  /* background-size: 100vw 100vh; */
  background-size: contain;
  background-repeat: no-repeat;
}
section.six {
  background-color: #fff;
}
section.six button i {
  font-size: 25px;
  color: #161616af;
}
section.six #innertext {
  color: #161616;
  bottom: 600px;
  right: 850px;
}
</style>
