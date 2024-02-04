<script>
export default {
  name: "AppHeader",
};
</script>
<template>
  <header class="NavBar container">
    <div class="logo">
      <img src="/img/dc-logo.png" alt="" />
    </div>
    <nav>
      <ul class="MainMenu">
        <li><a href="#">CHARACTERS</a></li>
        <li><a href="#" class="active">COMICS</a></li>
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
</template>

<style scoped>
.NavBar {
  display: flex;
  justify-content: space-between;
}
header {
  background-color: var(--dc-light);

  & .MainMenu {
    list-style: none;
    display: flex;
    justify-content: right;
    margin-top: 2rem;
    text-align: center;
  }
  & a {
    text-decoration: none;
    padding: 0.5rem 1rem;
    color: var(--dc-lgDark);
    font-weight: 600;
    font-size: large;
  }

  & a.active {
    background-color: aqua;
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
