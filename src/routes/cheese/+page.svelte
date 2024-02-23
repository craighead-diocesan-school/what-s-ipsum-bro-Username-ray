<script>
  import Header from "$lib/Header_cheese.svelte"
  import Nav from "$lib/Nav_cheese.svelte"
  import Footer from "$lib/Footer_cheese.svelte"
</script>

<Header />

<Nav />

<main>
  <h2>Pee-YOO Cheese Ipsum</h2>
  <div class="container">
    <p class="paragraph1">Cheesy grin parmesan taleggio. Brie boursin pecorino cheesy feet taleggio hard cheese roquefort when the cheese comes out everybody's happy. St. agur blue cheese port-salut bocconcini cheesecake rubber cheese mozzarella stilton cheese strings. Bocconcini.</p>

    <p class="paragraph2">Fromage the big cheese camembert de normandie. Cut the cheese gouda brie the big cheese when the cheese comes out everybody's happy squirty cheese cut the cheese gouda. Boursin cottage cheese cheeseburger camembert de normandie cheese slices goat port-salut danish fontina. Emmental caerphilly cream cheese mozzarella camembert de normandie cheesy feet.</p>

    <div class="image">
      <img src="cheese-plate.jpg" alt="Cheese Plate" />
    </div>
  </div>
</main>

<div class="wave"></div>

<Footer name="Ray Maeda" />

<style>
  main {
    background: #f8f69d;
    font-family: "Josefin Sans", sans-serif;
    padding-bottom: 20px;
    font-size: 120%;
  }
  h2 {
    text-align: center;
    padding: 20px;
  }
  .paragraph1 {
    font-size: 110%;
    line-height: 40px;
    position: absolute;
    top: 30%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: azure;
    width: 900px;
    filter: drop-shadow(4px 4px 2px #d7faff);
  }
  .paragraph2 {
    font-size: 110%;
    line-height: 40px;
    position: absolute;
    top: 70%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: azure;
    width: 900px;
    filter: drop-shadow(4px 4px 2px #d7faff);
  }
  img {
    width: 1000px;
    height: auto;
  }
  .image {
    text-align: center;
    padding-bottom: 20px;
  }
  .container {
    width: 1000px;
    height: 600px;
    position: relative;
    margin: 0% 15% 10% 15%;
  }
  .wave {
    --mask: radial-gradient(52.5px at 50% calc(100% - 74px), #000 99%, #0000 101%) calc(50% - 80px) 0/160px 100%, radial-gradient(52.5px at 50% calc(100% + 34px), #0000 99%, #000 101%) 50% calc(100% - 40px) / 160px 100% repeat-x;
    mask: var(--mask);
    background: #ffb060;
    height: 70px;
  }
  .wave:hover {
    transform: scale(1.1, 1.5);
    transition: 0.5s;
  }
</style>
