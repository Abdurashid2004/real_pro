<template>
    <div class="container">
        <div v-for="item in items" :key="item.id">
            <img :src="item.image" alt="image">
            <h2>{{ item.name }}</h2>
            <p>{{ item.text }}</p>
            <div class="flex gap-2">
                <span>{{ item.title }}</span>
                 
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>