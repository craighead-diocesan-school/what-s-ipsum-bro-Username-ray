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
  <div class="wave"></div>
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
  main {
    background: #fcd4e8;
    padding-bottom: 3rem;
  }

  /* wave effect generated at https://css-generators.com/custom-borders/ */
  .wave {
    --mask: radial-gradient(52.5px at 50% calc(100% - 74px), #000 99%, #0000 101%) calc(50% - 80px) 0/160px 100%, radial-gradient(52.5px at 50% calc(100% + 34px), #0000 99%, #000 101%) 50% calc(100% - 40px) / 160px 100% repeat-x;
    mask: var(--mask);
    background: #f2e6f7;
    height: 70px;
  }
</style>
