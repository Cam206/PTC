<script>
    export let answer = true;
</script>

{#if answer}
  <p> Good job!</p>
{:else}
<p> Not quite...</p>
{/if}