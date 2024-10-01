<script>
    import "../app.css";
    import Navbar from "$lib/components/Navbar.svelte";
</script>

<Navbar />
<div class="md:px-[24px] h-screen w-full">
    <slot />
</div>
