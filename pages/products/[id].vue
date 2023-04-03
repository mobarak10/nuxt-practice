<template>
    <div>
        <p>Product details for {{ id }}</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo animi, sit, fugit consectetur facilis cupiditate ratione facere illo ipsum et error ipsam laborum officiis cumque architecto quidem dolore doloremque totam?</p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params

    definePageMeta({
        layout: 'products'
    })
</script>

<style scoped>

</style>