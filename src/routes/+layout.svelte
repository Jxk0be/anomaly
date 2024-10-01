<script>
    import "../app.css";
    import Navbar from "$lib/components/Navbar.svelte";
</script>

<Navbar />
<div class="lg:px-[24px] h-screen w-full px-[16px]">
    <slot />
</div>
