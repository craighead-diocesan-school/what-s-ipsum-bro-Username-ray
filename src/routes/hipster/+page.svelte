<script>
  import Header from "$lib/Header.svelte"
  import Nav from "$lib/Nav.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<Header />

<Nav />

<main>
  <h2>You Probably Haven't Heard of Hipster Ipsum</h2>

  <p>Fingerstache tofu pickled vibecession kitsch lyft blackbird spyplane vegan craft beer keytar banh mi thundercats. Hashtag heirloom vape scenester paleo hexagon. Blackbird spyplane pok pok DIY heirloom scenester food truck kale chips pabst, bitters raw denim artisan waistcoat seitan freegan.</p>

  <p>Put a bird on it vibecession fashion axe YOLO asymmetrical. VHS photo booth listicle fam truffaut subway tile yr cred chicharrones semiotics biodiesel green juice microdosing whatever. Truffaut praxis PBR and B tattooed street art. Prism jean shorts pickled vegan. Vegan praxis cronut kitsch pop-up. Letterpress street art mlkshk marxism.</p>
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
