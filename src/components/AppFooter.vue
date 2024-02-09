<script>
export default {
  name: "AppFooter",
};
</script>
<template>
  <footer>
    <div class="top">
      <div class="container">
        <div class="row">
          <div class="col">
            <ul class="list-unstyled leftmenu">
              <h3>DC COMICS</h3>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <h3>SHOP</h3>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
            </ul>
          </div>
          <div class="col">
            <ul class="list-unstyled middlemenu">
              <h3>DC</h3>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
            </ul>
          </div>
          <div class="col">
            <ul class="list-unstyled rightmenu">
              <h3>SITES</h3>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
              <li><a href="#">Lorem</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </footer>
  <div class="logobig">
    <img src="./img/dc-logo-bg.png" alt="" />
  </div>
  <div class="bottom"></div>
  <div class="bottommenu container">
    <div class="signup">
      <button>SIGN-UP NOW</button>
    </div>
    <div class="followusmenu">
      <ul>
        <li>
          <a href="#"><img src="./img/footer-facebook.png" alt="" /></a>
        </li>
        <li>
          <a href="#"><img src="./img/footer-twitter.png" alt="" /></a>
        </li>
        <li>
          <a href="#"><img src="./img/footer-youtube.png" alt="" /></a>
        </li>
        <li>
          <a href="#"><img src="./img/footer-pinterest.png" alt="" /></a>
        </li>
        <li>
          <a href="#"><img src="./img/footer-periscope.png" alt="" /></a>
        </li>
      </ul>
    </div>
  </div>
</template>
<style scoped>
footer {
  padding: 1rem 0;
  & > .top {
    background-image: url("./img/footer-bg.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: top;
    & h3 {
      color: var(--dc-light);
      margin: 1.5rem 0;
    }
    & ul a {
      color: lightgrey;
      text-decoration: none;
      line-height: 1.5rem;
    }
  }
}
</style>
