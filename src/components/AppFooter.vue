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
    <div class="bottom">
      <div class="container">
        <a href="" class="signup">Sign-up now!</a>
        <div class="social">
          <strong>Follow us</strong>
          <a href=""><img src="./img/footer-facebook.png" alt="" /></a>
          <a href=""><img src="./img/footer-twitter.png" alt="" /></a>
          <a href=""><img src="./img/footer-youtube.png" alt="" /></a>
          <a href=""><img src="./img/footer-pinterest.png" alt="" /></a>
          <a href=""><img src="./img/footer-periscope.png" alt="" /></a>
        </div>
      </div>
    </div>
  </footer>
</template>
<style scoped>
footer {
  & > .top {
    background-image: url("./img/dc-logo-bg.png"), url("./img/footer-bg.jpg");
    background-repeat: no-repeat;
    background-size: 500px, cover;
    background-position: 80%, top;
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

  & > .bottom {
    & .container {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    & .signup {
      border: 1px solid var(--dc-blue);
      padding: 0.75rem;
      color: var(--dc-light);
      text-transform: uppercase;
    }

    & .social {
      display: flex;
      align-items: center;
      gap: 1rem;
    }

    & strong {
      text-transform: uppercase;
      color: var(--dc-light);
    }
  }
}
</style>
