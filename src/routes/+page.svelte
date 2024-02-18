<script>
  import Header from "$lib/Header.svelte"
  import Nav from "$lib/Nav.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<Header />

<Nav />

<main>
  <div class="columns">
    <div class="text">
      <h2>Lorem Ipsum with Flavour</h2>
    </div>
  </div>

  <div class="columns">
    <div class="text">
      <p>What's Ipsum Bro is a lorem ipsum generator with a twist. Instead of the same old boring lorem ipsum, you can choose from a variety of flavours to spice up your placeholder text.</p>
    </div>
  </div>

  <div class="columns">
    <div class="boxes">
      <a href="pirate">
        <img src="pirate.png" alt="Pirate" class="box" />
      </a>
    </div>
  </div>
  <div class="columns">
    <div class="boxes">
      <a href="cheese">
        <img src="cheese.png" alt="Cheese" class="box" />
      </a>
    </div>
  </div>
  <div class="columns">
    <div class="boxes">
      <a href="cupcake">
        <img src="cupcake.png" alt="Cupcake" class="box" />
      </a>
    </div>
  </div>
  <div class="columns">
    <div class="boxes">
      <a href="hipster">
        <img src="hipster.png" alt="Hipster" class="box" />
      </a>
    </div>
  </div>
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
  .boxes {
    display: flex;
    flex-wrap: wrap;
    gap: 25px;
    justify-content: space-between;
    width: 400px;
  }
  .text {
    font-family: "Kode Mono", monospace;
    width: 30%;
  }

  h2 {
    text-align: center;
  }
  .columns {
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    background: #f2e6f7;
    padding: 5rem 10rem;
  }
  @media screen and (max-width: 600px) {
    .columns {
      flex-direction: column;
      padding: 2rem 3rem;
    }

    .text {
      width: 100%;
    }
  }
</style>
