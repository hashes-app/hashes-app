<script>
	import Nav from '../components/Nav.svelte';
	import Footer from '../components/Footer.svelte';
	export let segment;
</script>

<style>
  main {
    max-width: 60em;
  }
</style>

<Nav {segment} />

<main mx="auto" px="6">
  <slot></slot>
</main>

<!-- <Footer /> -->