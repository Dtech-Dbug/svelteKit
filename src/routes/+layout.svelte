<script>
	import Header from './Header.svelte';
	import '../app.css';
</script>

<div class="app">
	<!-- <Header /> -->

	<main class='layout'>
        <div class="container">
          <slot />
      </div>
  </main>
</div>

<style>
	.app {
		display: flex;
		flex-direction: column;
    height: 100%;
		padding: 1rem;
		position: relative;
		background: linear-gradient(to right, #fc466b, #3f5efb);
		padding: 0.3rem;
	}

	/* main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		max-width: 64rem;
		margin: 0 auto;
		box-sizing: border-box;
	} */

.layout {
  /* background-color: black; */
  height: 100vh;
  border-radius: 0.75rem;
}

	/* @media (min-width: 480px) {
		footer {
			padding: 12px 0;
		}
	} */
</style>
