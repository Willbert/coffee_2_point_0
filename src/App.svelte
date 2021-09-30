<script>
  import logo from './assets/coffee2point0.png'
  import Counter from './lib/Counter.svelte'
  import Coffee from './lib/coffee.svelte'
</script>

<main>
  <img src={logo} alt="Svelte Logo" />

  <Coffee />

</main>

<style>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
      Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }

  main {
    text-align: center;
    padding: 1em;
    margin: 0 auto;
  }

  img {
    height: 20rem;
    width: 29rem;
  }
</style>
