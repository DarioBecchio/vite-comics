<script>
export default {
  name: "AppMain",
};
</script>
<template>
  <div class="cardmenu container">CONTENT GOES HERE</div>
  <div class="lowermenu">
    <ul class="shopsbar container">
      <li>
        <a href="#"
          ><img src="/img/buy-comics-digital-comics.png" alt="" /> DIGITAL
          COMICS</a
        >
      </li>
      <li>
        <a href="#"
          ><img src="/img/buy-comics-merchandise.png" alt="" />DC MERCHANDISE</a
        >
      </li>
      <li>
        <a href="#"
          ><img src="/img/buy-comics-subscriptions.png" alt="" />SUBSCRIPTION</a
        >
      </li>
      <li>
        <a href="#"
          ><img src="/img/buy-comics-shop-locator.png" alt="" />COMIC SHOP
          LOCATOR</a
        >
      </li>
      <li>
        <a href="#"
          ><img src="/img/buy-dc-power-visa.svg" alt="" />DC POWER VISA</a
        >
      </li>
    </ul>
  </div>
</template>

<style>
.container {
  width: 70%;
  max-width: 1176px;
  margin: auto;
}
.cardmenu {
  background-color: var(--dc-darker);
  height: 300px;
}
.lowermenu {
  background-color: var(--dc-blue);
}
.shopsbar {
  display: flex;
  justify-content: space-around;
  list-style: none;
  align-items: center;
  & a {
    text-decoration: none;
    display: flex;
    align-items: center;
    color: var(--dc-light);
  }
}
</style>
