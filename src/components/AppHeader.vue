<script>
export default {
  name: "AppHeader",
};
</script>
<template>
  <header>
    <nav class="container">
      <div class="logo">
        <img src="/img/dc-logo.png" alt="" />
      </div>
      <ul>
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
header {
  background-color: var(--dc-light);

  & nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  & .logo > img {
    width: 70px;
  }
  & ul {
    display: flex;
    gap: 1rem;
    margin-top: 0;
    margin-bottom: 0;
  }
  & ul > li {
    list-style: none;
    padding: 2rem 0;
    border-bottom: 4px solid transparent;
  }

  & ul > li:hover {
    border-bottom: 4px solid var(--dc-blue);
  }
  & a {
    text-decoration: none;
    color: var(--dc-lgDark);
    font-weight: 600;
  }
}
</style>
