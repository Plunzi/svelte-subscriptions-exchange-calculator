<script>
  import Calculator from './lib/Calculator.svelte'
</script>

<main>
  <div class="container">
    <h1>Abonnement Calculator</h1>
  
    <div class="card">
      <Calculator />
    </div>
  
    <p>
      We get all our exchange information from <a href="https://open.er-api.com/">open.er-api.com</a>.<br>
      We don't save/store any of your data. Everything is stored locally on your device.<br>
      Check out the source code which was used to built this app.
    </p>
  
    <p class="read-the-docs">
      Github Repository containing the source. (<a href="https://github.com/Plunzi/svelte-subscriptions-exchange-calculator">click here</a>)
    </p>
  </div>
</main>

<style>
  .card {
    display: flex;
    flex-direction: column;
    gap: 1rem;
  }

  h1 {
    margin-block-start: 0rem;
    margin-block-end: 2rem;
  }

  .read-the-docs {
    color: #888;
  }
  
  :global(body) {
    background-color: #f7f8fc;
  }

  main {
    padding: 2rem;
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
