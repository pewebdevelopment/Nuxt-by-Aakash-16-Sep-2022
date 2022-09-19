<template>
    <p>Welcome Aakash</p>

    <!-- here nuxt will replace page content -->
    <slot></slot>
</template>

<script>
    definePageMeta({
        layout: 'sidebar'
    })
</script>
