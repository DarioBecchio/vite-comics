<script>
export default {
  name: "AppFooter",
};
</script>
<template>
  <div class="resume container">
    <div class="footermenu">
      <div class="linkmenu">
        <ul class="leftmenu">
          <h3>DC COMICS</h3>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
          <h3>SHOP</h3>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
        </ul>
        <ul class="middlemenu">
          <h3>DC</h3>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
        </ul>
        <ul class="rightmenu">
          <h3>SITES</h3>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
        </ul>
      </div>
      <div class="logobig">
        <img src="./img/dc-logo-bg.png" alt="" />
      </div>
    </div>
  </div>
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
<style>
.container {
  width: 70%;
  max-width: 1176px;
  margin: auto;
}
.resume {
  background-image: url("./img/footer-bg.jpg");
}
.linkmenu {
  display: flex;
  list-style: none;
}
.footermenu {
  display: flex;
  justify-content: space-between;
}
.bottommenu {
  display: flex;
  justify-content: space-between;
  background-color: var(--dc-lgDark);
}
.followusmenu {
  display: flex;
}
</style>
