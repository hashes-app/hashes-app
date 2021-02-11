<script>
	import Nav from '../components/Nav.svelte';
	// import Footer from '../components/Footer.svelte';
	export let segment;
</script>

<style>
  main {
    max-width: 56em;
    height: 100vh;
  }
</style>

<Nav {segment} />

<main mx="auto">
  <slot></slot>
</main>