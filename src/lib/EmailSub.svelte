<script lang="ts">
let yes = false
const handleOnClick = () => {
  alert("We will Start Spamming You!")
}
</script>

<input bind:checked={yes} type="checkbox" /> Send spam email!

{#if yes}
<p>Yay!, We Will start to spam you soon!</p>
{:else}
<p>Click to get Spammed!</p>
{/if}

<button disabled={!yes} on:click={handleOnClick}>Spam Me</button>