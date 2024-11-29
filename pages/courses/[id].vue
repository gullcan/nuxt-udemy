<template>
    <div>
        <p>Courses details for {{ id }}</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde, cumque!</p>
    </div>
</template>
    
    <script setup>
    const { id } = useRoute().params

    definePageMeta({
            layout: 'courses'
        })
    </script>
    
    <style scoped>

    </style>