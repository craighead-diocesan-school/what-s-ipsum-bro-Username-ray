<nav>
  <div class="boxes">
    <a href="/" class="box">Home</a>
    <a href="/pirate" class="box">Pirate</a>
    <a href="/cheese" class="box">Cheese</a>
    <a href="/cupcake" class="box">Cupcake</a>
    <a href="/hipster" class="box">Hipster</a>
  </div>
</nav>

<style>
  nav {
    background: #e09fce;
    font-family: "Caveat", cursiv;
    font-size: 150%;
  }
  .box {
    text-align: center;
    width: 125px;
    height: 25px;
    border-radius: 5%;
    padding: 6px 10px 14px 10px;
    background: ivory;
    box-shadow: 5px 5px #fc5c9c;
    margin: 30px 20px;
  }
  .box:hover {
    transform: scale(1.1);
    transition: 0.25s;
  }
  .boxes {
    display: flex;
    gap: 25px;
    justify-content: space-around;
  }
</style>
