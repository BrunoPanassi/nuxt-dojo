<template>
    <div>
        <p>Checkout out this id: {{ id }}</p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params
</script>

<style scoped>

</style>