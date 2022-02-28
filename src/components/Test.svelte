<script>
  let name = "Stepg"
</script>

<style lang="scss">
  div {
    margin: 1em;

    button { 
      background-color: plum;
    }
  }
</style>

<div>
  <button on:click={() => name = "PegS"}>Click to change !</button>
  <p>Hello {name}</p>
</div>