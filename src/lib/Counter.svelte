<script>
  let count = 0
  const increment = () => {
    count += 1
  }
</script>

<button on:click={increment}>
  Clicks: {count}
</button>

<style>
  button {
    font-family: inherit;
    font-size: inherit;
    padding: 1em 2em;
    color: #ff3e00;
    background-color: rgba(187, 187, 187, 0.1);
    border-radius: 6px;
    /* border: 2px solid rgba(255, 62, 0, 0); */
    /* outline: none; */
    /* width: 200px; */
    border: 1px solid #ff3e00;
    font-variant-numeric: tabular-nums;
    cursor: pointer;
  }

  button:hover {
    transform: translateX(-1px) translateY(-1px);
    background-color: rgba(187, 187, 187, 0.3);
  }

  button:active {
    background-color: rgba(187, 187, 187, 0.5);
  }
</style>
