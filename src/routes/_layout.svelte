<!-- layout.js  -->
<script>
    import Header from '../components/Header.svelte';
    export let segment;
</script>

<!-- layout.html  -->
<Header { segment } />

<main>
    <slot />
</main>