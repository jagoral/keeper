<script>
  import Nav from 'components/Nav.svelte';
  import './_theme.scss';

  export let segment;
</script>

<Nav {segment} />

<main class="main-main">
  <slot />
</main>
