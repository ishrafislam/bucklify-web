<script setup>
    import Navbar from './components/Navbar.vue'
</script>

<template>
    <Navbar></Navbar>
    <div class="container mt-3">
        <RouterView />
    </div>
</template>
