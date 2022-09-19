<template>
    <div class="bg-red-700">
    <button @click="moveToAbout"> Take me to About </button>
    Hello Aakash Shendage
    </div>
</template>

<script setup>

import '@/assets/css/main.css'
    function moveToAbout() {
        navigateTo("about");
    }
</script>