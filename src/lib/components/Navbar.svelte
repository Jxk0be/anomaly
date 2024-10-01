<script>
    import Icon from '@iconify/svelte';
</script>

<div class="w-full fixed h-[70px] bg-white border-b-[1px] border-black/10">
    <div class="lg:px-[24px] px-[16px] h-full w-full  flex items-center justify-between">
        <a href="/">Classified Map of Anomalies</a>

        <button class={`lg:hidden text-[35px] text-black transition-all ease-in-out rounded-xl duration-150`}>
            <Icon icon="lucide:menu" />
        </button>

        <div class="hidden lg:flex w-auto items-center justify-between">
            <a href="/" class="mr-8">Anomaly Map</a>
            <a href="/about" class="mr-8">ABOUT C.M.O.A.</a>
            <a href="/account" class="">My Account</a>
        </div>
    </div>
</div>