<script>
  import Header from "$lib/Header_cupcake.svelte"
  import Nav from "$lib/Nav_cupcake.svelte"
  import Footer from "$lib/Footer_cupcake.svelte"
</script>

<Header />

<Nav />

<main>
  <h2>Yum Cupcake Ipsum</h2>

  <div class="container">
    <div class="grid-item">
      <div class="image">
        <img src="cupcake-hall.jpg" alt="Cupcake hall" />
      </div>
    </div>
    <div class="grid-item">
      <p>Halvah liquorice apple pie jelly beans chupa chups candy icing tiramisu. Tart jelly jujubes gingerbread croissant biscuit. Chupa chups tart cheesecake lemon drops dragée chocolate bar dessert. Ice cream ice cream sugar plum jujubes dragée topping tiramisu croissant chocolate.</p>

      <p>Jujubes tiramisu gingerbread cake donut chocolate bar tart marzipan pastry. Gingerbread jelly tootsie roll muffin bear claw muffin. Jelly-o fruitcake chocolate bar chupa chups chocolate sesame snaps candy. Sweet roll carrot cake cake jelly candy jujubes gummi bears jelly-o. Oat cake wafer chocolate bar sweet roll macaroon soufflé powder sugar plum tart.</p>
    </div>
  </div>
</main>

<div class="wave"></div>

<Footer name="Ray Maeda" />

<style>
  main {
    background: #e09fce;
    font-family: "Caveat", cursive;
    font-size: 150%;
    padding-bottom: 20px;
  }
  h2 {
    text-align: center;
    padding: 20px;
    font-size: 120%;
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
    background: #fc5c9c;
    height: 70px;
  }
  .wave:hover {
    transform: scale(1.1, 1.5);
    transition: 0.5s;
  }
</style>
