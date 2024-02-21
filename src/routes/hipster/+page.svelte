<script>
  import Header from "$lib/Header_hipster.svelte"
  import Nav from "$lib/Nav_hipster.svelte"
  import Footer from "$lib/Footer_hipster.svelte"
</script>

<Header />

<Nav />

<main>
  <h2>You Probably Haven't Heard of Hipster Ipsum</h2>

  <p>Fingerstache tofu pickled vibecession kitsch lyft blackbird spyplane vegan craft beer keytar banh mi thundercats. Hashtag heirloom vape scenester paleo hexagon. Blackbird spyplane pok pok DIY heirloom scenester food truck kale chips pabst, bitters raw denim artisan waistcoat seitan freegan.</p>

  <p>Put a bird on it vibecession fashion axe YOLO asymmetrical. VHS photo booth listicle fam truffaut subway tile yr cred chicharrones semiotics biodiesel green juice microdosing whatever. Truffaut praxis PBR and B tattooed street art. Prism jean shorts pickled vegan. Vegan praxis cronut kitsch pop-up. Letterpress street art mlkshk marxism.</p>

  <div class="image">
    <img src="man.jpg" alt="Hipster" />
  </div>
</main>

<div class="wave"></div>

<Footer name="Ray Maeda" />

<style>
  main {
    background: linear-gradient(45deg, #2cd9cd 0%, #c5c1ff 56%, #f3bccc 100%);
    font-family: "Barriecito", system-ui;
    padding-bottom: 20px;
    font-size: 120%;
  }
  h2 {
    text-align: center;
    padding: 20px;
  }
  p {
    padding: 20px 100px;
    line-height: 30px;
  }
  img {
    width: 700px;
    height: auto;
  }
  .image {
    text-align: center;
    padding-bottom: 20px;
  }
  .wave {
    --mask: radial-gradient(52.5px at 50% calc(100% - 74px), #000 99%, #0000 101%) calc(50% - 80px) 0/160px 100%, radial-gradient(52.5px at 50% calc(100% + 34px), #0000 99%, #000 101%) 50% calc(100% - 40px) / 160px 100% repeat-x;
    mask: var(--mask);
    background: #fc5c9c;
    height: 70px;
  }
  .wave:hover {
    transform: scale(1.1, 1.5);
    transition: 0.5s;
  }
</style>
