<script>
import AppJumbotron from "./AppJumbotron.vue";
import ComicCards from "./ComicCards.vue";
export default {
  name: "AppMain",
  components: {
    AppJumbotron,
    ComicCards,
  },
  data() {
    return {
      cards: [
        {
          thumb: "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
          price: "$19.99",
          series: "Action Comics",
          type: "comic book",
        },
        {
          thumb:
            "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
          price: "$3.99",
          series: "American Vampire 1976",
          type: "comic book",
        },
        {
          thumb:
            "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
          price: "$16.99",
          series: "Aquaman",
          type: "graphic novel",
        },
        {
          thumb: "https://d29xot63vimef3.cloudfront.net/image/batgirl/1-1.jpg",
          price: "$2.99",
          series: "Batgirl",
          type: "comic book",
        },
        {
          thumb:
            "https://static.posters.cz/image/750/locandine-film-in-plexiglass-batman-prowl-comic-cover-i69653.jpg",
          price: "$3.99",
          series: "Batman",
          type: "comic book",
        },
        {
          thumb:
            "https://static.wikia.nocookie.net/marvel_dc/images/5/50/Batman_Beyond_v.1_1.jpg",
          price: "$2.99",
          series: "Batman Beyond",
          type: "comic book",
        },
        {
          thumb:
            "https://static.wikia.nocookie.net/marvel_dc/images/0/0d/Batman_Superman_Vol_1_1.jpg",
          price: "$3.99",
          series: "Batman/Superman",
          type: "comic book",
        },
        {
          thumb:
            "https://static.wikia.nocookie.net/marvel_dc/images/c/cf/Batman_Superman_Annual_Vol_2_1.jpg",
          price: "$4.99",
          series: "Batman/Superman Annual",
          type: "comic book",
        },
        {
          thumb:
            "https://static.wikia.nocookie.net/marvel_dc/images/5/54/Batman_The_Joker_War_Zone_Vol_1_1.jpg",
          price: "$5.99",
          series: "Batman: The Joker War Zone",
          type: "comic book",
        },
        {
          thumb:
            "https://static.wikia.nocookie.net/marvel_dc/images/6/64/Batman_Three_Jokers_Collected.jpg",
          price: "$6.99",
          series: "Batman: Three Jokers",
          type: "comic book",
        },
        {
          thumb:
            "https://static.wikia.nocookie.net/marvel_dc/images/f/f8/Batman_White_Knight_Presents_Harley_Quinn_Vol_1_1.jpg",
          price: "$4.99",
          series: "Batman: White Knight Presents: Harley Quinn",
          type: "comic book",
        },
        {
          thumb:
            "https://static.wikia.nocookie.net/marvel_dc/images/c/c8/Catwoman_Vol_2_1.jpg",
          price: "$16.99",
          series: "Catwoman",
          type: "graphic novel",
        },
      ],
    };
  },
};
</script>
<template>
  <main>
    <AppJumbotron></AppJumbotron>
    <!-- Section prodotti -->
    <section class="comics">
      <div class="container">
        <h3>Current series</h3>
        <div class="row">
          <div class="col-12 col-md-4 col-lg-2" v-for="card in cards">
            <ComicCards :card="card"></ComicCards>
          </div>
        </div>
      </div>
    </section>
    <!-- Banner -->
    <div class="banner">
      <div class="container">
        <div class="item">
          <img height="60" src="/img/buy-comics-digital-comics.png" alt="" />
          <span>Digital comics</span>
        </div>
        <div class="item">
          <img height="60" src="/img/buy-comics-merchandise.png" alt="" />
        </div>
        <div class="item">
          <img height="60" src="/img/buy-comics-subscriptions.png" alt="" />
        </div>
        <div class="item">
          <img height="60" src="/img/buy-comics-shop-locator.png" alt="" />
        </div>
        <div class="item">
          <img height="60" src="/img/buy-dc-power-visa.svg" alt="" />
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped>
.comics {
  & h3 {
    display: inline-block;
    padding: 1rem 2rem;
    background-color: var(--dc-blue);
    color: var(--dc-light);
    margin: -2rem 0 0.5rem;
  }
}
.banner {
  background-color: var(--dc-blue);
  padding: 2rem 0;
  & > .container {
    display: flex;
    justify-content: space-evenly;
  }
  & .item {
    display: flex;
    align-items: center;
    gap: 1rem;
  }
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
