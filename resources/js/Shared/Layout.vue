<template>

    <section class="p-6 bg-gray-200">
        <header class="flex">
    
            <h1 class="font-bold text-lg">My App</h1>
            <Nav></Nav>
    
        </header>

    </section>

    <section class="p-6">
        
        <slot></slot>

    </section>

</template>

<script>

import Nav from './Nav.vue';

export default {
    components: { Nav },

};

</script>

<style>

</style>