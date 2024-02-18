<script>
  import Header from "$lib/Header.svelte"
  import Nav from "$lib/Nav.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<Header />

<Nav />

<main>
  <h2>Lorem Ipsum with Flavour</h2>

  <p>What's Ipsum Bro is a lorem ipsum generator with a twist. Instead of the same old boring lorem ipsum, you can choose from a variety of flavours to spice up your placeholder text.</p>

  <a href="pirate">
    <img src="pirate.png" alt="Pirate" class="box" />
  </a>
  <a href="cheese">
    <img src="cheese.png" alt="Cheese" class="box" />
  </a>
  <a href="cupcake">
    <img src="cupcake.png" alt="Cupcake" class="box" />
  </a>
  <a href="hipster">
    <img src="hipster.png" alt="Hipster" class="box" />
  </a>
</main>

<Footer />

<style>
  .box {
    width: 125px;
    height: 125px;
    border-radius: 5%;
    padding: 25px;
    background: ivory;
    box-shadow: 10px 10px #fcd4e8;
  }
</style>
