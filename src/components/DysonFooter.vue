<template>
  <footer class="section">
    <div class="container">
      <div class="text-center">
        <span class="logo"><a to="/">dyson</a></span>
      </div>
      <div class="text-center mt-3">
        <span class="footer-icon"
          ><a href="#"><i class="fa-brands fa-facebook-f"></i></a
        ></span>
        <span class="footer-icon"
          ><a href="#"><i class="fa-brands fa-instagram"></i></a
        ></span>
        <span class="footer-icon"
          ><a href="#"><i class="fa-brands fa-pinterest"></i></a
        ></span>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
* a {
  text-decoration: none;
  color: #fff;
}
* a:hover {
  color: #fff;
}
footer {
  background-color: #161616;
  height: 150px;
  display: flex;
  align-items: center;
}
footer .logo {
  margin: 0;
  color: #fff;
  font-size: 2rem;
  font-family: "Merienda", cursive;
}
footer .footer-icon {
  margin: 0 10px;
  font-size: 25px;
}
span {
  line-height: normal;
}
</style>
