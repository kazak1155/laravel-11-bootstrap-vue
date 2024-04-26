<script setup>
import { ref } from 'vue'

const counter = ref(0)
</script>

<template>
    <button
        type="button"
        @click="counter++"
    >
        <h1>Counter</h1>
        Counter is: {{ counter }}
    </button>
</template>
