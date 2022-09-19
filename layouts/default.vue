<template>
    <div>
        <nav class="bg-purple-700 text-white">
        <NuxtLink to="/">Home</NuxtLink>
        <br>
        <NuxtLink to="about">About</NuxtLink>
        <br>
        <NuxtLink to="profile">Profile</NuxtLink>
        <br>
    </nav>
    

    <!-- here nuxt will replace page content -->
   <slot></slot>
</div>
</template>

<script>
   
</script>