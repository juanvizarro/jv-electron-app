<script setup lang="ts">
    import { ref } from 'vue'
    const text = ref('')
    console.log('👋 This message is being logged by "App.vue", included via Vite');
</script>
<template>
    <h1>My Electron App</h1>
    <p>Welcome my Electron application with Vue.</p>
    <div class="text-wrapper">
        <input v-model="text" />
        <span>text ref: {{ text }}</span>
    </div>
</template>
<style>
.text-wrapper{
    display: flex;
    flex-direction: column;
    gap: 2;
}
</style>