<script lang="ts">
  import Counter from './lib/Counter.svelte'
  import EmailSub from './lib/EmailSub.svelte'
</script>

<main>
  <div class="card">
  <p>Click to Count</p>
    <Counter />
  </div>
      <EmailSub />
</main>

<style>
main{
  border: 1px solid blue;
  padding: 2rem;
  border-radius: 2rem;
}
</style>
