<script>
  import Header from "$lib/Header.svelte"
  import Nav from "$lib/Nav.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<Header />

<Nav />

<main>
  <h2>Yar Pirate Ipsum</h2>

  <p>Maroon square-rigged rope's end spirits fathom tackle bilge rat careen cackle fruit splice the main brace. Arr to go on account bilge six pounders smartly yo-ho-ho yawl tack boatswain maroon. Barque hogshead coffer Buccaneer loot fire ship Shiver me timbers Blimey salmagundi reef.</p>

  <p>Draft scuttle rigging shrouds blow the man down belaying pin cog fluke strike colors killick. Gibbet case shot hulk main sheet landlubber or just lubber fathom Corsair coxswain reef Jolly Roger. Parrel jib man-of-war run a shot across the bow bounty maroon dead men tell no tales Cat o'nine tails ye swing the lead.</p>
</main>

<Footer name="Ray Maeda" />

<style>
  main {
    background: #f2e6f7;
    font-family: "Kode Mono", monospace;
  }
  h2 {
    text-align: center;
    padding: 20px;
  }
  p {
    padding: 20px 100px;
    line-height: 30px;
  }
</style>
