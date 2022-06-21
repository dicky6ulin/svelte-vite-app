<script>
	import { nama } from './css/Style.js';
</script>

<main>
  <hr />
  <p>ini adalah sebuah component <span class="nama">SVELTE</span> lain</p>
  <p>Ini adalah dari css <b><span class={nama}>global</span></b></p>
</main>

<style>
  .nama {
    color: palevioletred;
  }
</style>
