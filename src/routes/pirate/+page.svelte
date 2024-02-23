<script>
  import Header from "$lib/Header_pirate.svelte"
  import Nav from "$lib/Nav_pirate.svelte"
  import Footer from "$lib/Footer_pirate.svelte"
</script>

<Header />

<Nav />

<main>
  <h2>Yar Pirate Ipsum</h2>
  <div class="container">
    <div class="grid-item">
      <p>Maroon square-rigged rope's end spirits fathom tackle bilge rat careen cackle fruit splice the main brace. Arr to go on account bilge six pounders smartly yo-ho-ho yawl tack boatswain maroon. Barque hogshead coffer Buccaneer loot fire ship Shiver me timbers Blimey salmagundi reef.</p>
      <p>Draft scuttle rigging shrouds blow the man down belaying pin cog fluke strike colors killick. Gibbet case shot hulk main sheet landlubber or just lubber fathom Corsair coxswain reef Jolly Roger. Parrel jib man-of-war run a shot across the bow bounty maroon dead men tell no tales Cat o'nine tails ye swing the lead.</p>
    </div>
    <div class="grid-item">
      <div class="image">
        <img src="lego-pirate.jpg" alt="Lego Pirate" />
      </div>
    </div>
  </div>
</main>

<div class="wave"></div>

<Footer name="Ray Maeda" />

<style>
  main {
    background: #0f0429;
    font-family: "Protest Revolution", sans-serif;
    padding-bottom: 20px;
    color: #ffffffd1;
  }
  h2 {
    text-align: center;
    padding: 20px;
  }
  p {
    padding: 20px 100px;
    line-height: 35px;
  }
  img {
    width: 700px;
    height: auto;
  }
  .image {
    text-align: center;
    padding: 0px 40px 20px 0px;
  }
  .container {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
  }
  .grid-item {
    text-align: center;
  }
  .wave {
    --mask: radial-gradient(52.5px at 50% calc(100% - 74px), #000 99%, #0000 101%) calc(50% - 80px) 0/160px 100%, radial-gradient(52.5px at 50% calc(100% + 34px), #0000 99%, #000 101%) 50% calc(100% - 40px) / 160px 100% repeat-x;
    mask: var(--mask);
    background: #516eef;
    height: 70px;
  }
  .wave:hover {
    transform: scale(1.1, 1.5);
    transition: 0.5s;
  }
</style>
