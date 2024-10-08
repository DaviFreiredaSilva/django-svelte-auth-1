<script>
    import Navbar from '$lib/components/Navbar.svelte'
</script>

<Navbar/>
<div class="p-3">
    <slot/>
</div>

<style>
    :global(body){
        background-color: black;
        color: white;
    }
</style>