<slot />

<style>
  /* Add your own fonts and global styles here. */
  @import url("https://fonts.googleapis.com/css2?family=Kode+Mono:wght@400..700&display=swap");
  @import url("https://fonts.googleapis.com/css2?family=Protest+Revolution&display=swap");
  @import url("https://fonts.googleapis.com/css2?family=Josefin+Sans:ital,wght@0,100..700;1,100..700&family=Protest+Revolution&display=swap");
  @import url("https://fonts.googleapis.com/css2?family=Caveat:wght@400..700&family=Josefin+Sans:ital,wght@0,100..700;1,100..700&family=Protest+Revolution&display=swap");
  @import url("https://fonts.googleapis.com/css2?family=Barriecito&display=swap");
  /* The code below resets the browser's default styles. It's a good idea to include this in your layout component. */
  :global(body) {
    margin: 0;
    padding: 0;
    font-family: sans-serif;
  }

  :global(a) {
    color: #1eaedb;
    text-decoration: none;
  }

  :global(a:hover) {
    color: #0fa0ce;
  }

  :global(h1) {
    font-size: 2rem;
    font-weight: 300;
    margin: 0 0 1rem 0;
  }

  :global(h2) {
    font-size: 1.5rem;
    font-weight: 300;
    margin: 0 0 1rem 0;
  }
</style>
