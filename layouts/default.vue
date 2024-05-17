<template>

    <MenuTopo />

    <SideNav />

    <section class="p-4 sm:ml-64">
        <div class="p-4 mt-12">
            <slot />
        </div>
    </section>

</template>

<script setup lang="ts">
    import { onMounted } from 'vue'
    import { initFlowbite } from 'flowbite'

    // initialize components based on data attribute selectors
    onMounted(() => {
        initFlowbite();
    })

</script>

<style lang="scss" scoped>

</style>