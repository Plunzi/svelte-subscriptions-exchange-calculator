<script>
  import Calculator from './lib/Calculator.svelte'
</script>

<main>
  <div class="container">
    <h1>Abonnements Calculator</h1>
  
    <div class="card">
      <Calculator />
    </div>
  
    <p>
      We get all our exchange information from <a href="https://open.er-api.com/">open.er-api.com</a>.<br>
      We don't save/store any of your data. Everything is stored locally on your device.<br>
      Check out the source code which was used to built this app.
    </p>
  
    <p class="read-the-docs">
      Github Repository containing the source. (<a href="https://github.com/plunzi/abonnements-calculator">click here</a>)
    </p>
  </div>
</main>

<style>
  .read-the-docs {
    color: #888;
  }
  :global(body) {
    background-image: url("/img/background.svg");
    background-size: 20rem;
    background-repeat: repeat 0 0;
    background-color: black;
  }

  main {
    padding: 2rem;
  }

  .container {
    width: 100%;
    height: 100%;
    background-color: rgb(0, 0, 0);
    border-radius: 1rem;
    padding: 1rem;
    border-width: 1px;
    border-style: solid;
    border-color: #888;
  }

  @media only screen and (max-width: 500px) {
    main {
      padding: 0;
    }
  }

  @media only screen and (max-width: 300px) {
    h1 {
      margin-block-end: 1rem;
    }
  }
</style>
