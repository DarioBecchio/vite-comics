<script>
export default {
  name: "AppHeader",
};
</script>

<header class="NavBar container">
    <div class="logo">
      <img src="/img/dc-logo.png" alt="" />
    </div>
    <nav>
      <ul class="MainMenu">
        <li><a href="#">CHARACTERS</a></li>
        <li><a href="#">COMICS</a></li>
        <li><a href="#">MOVIES</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">GAME</a></li>
        <li><a href="#">COLLECTIBLES</a></li>
        <li><a href="#">VIDEOS</a></li>
        <li><a href="#">FANS</a></li>
        <li><a href="#">NEWS</a></li>
        <li><a href="#">SHOP</a></li>
      </ul>
    </nav>
  </header>
<style scoped>
.NavBar {
  display: flex;
  justify-content: space-between;
}

li {
  list-style: none;
  & a {
    text-decoration: none;
    margin-left: 0.5rem;
  }
}

.container {
  width: 70%;
  max-width: 1176px;
  margin: auto;
}
.MainMenu {
  display: flex;
  justify-content: space-between;
}
</style>
