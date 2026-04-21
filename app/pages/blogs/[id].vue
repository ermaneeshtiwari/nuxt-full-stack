<script setup>
     // Get the dynamic route parameter 'id' using useRoute
        const route = useRoute();
        const blogId = route.params.id;
</script>

<template>
    <div>
        <h1>Blog Details of {{ blogId  }}</h1>
        <p>This is the page for displaying a specific blog post.</p>
    </div>
</template>