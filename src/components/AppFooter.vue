<script>
export default {
  name: "AppFooter",
};
</script>
<template>
  <div class="resume">
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
  <div class="followmenu">
    <div class="signup"></div>
  </div>
</template>
<style>
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
.followmenu {
}
</style>
