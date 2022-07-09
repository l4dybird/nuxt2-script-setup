<script setup lang="ts">
import { ref } from '@nuxtjs/composition-api';

const hoge = ref<string>("Nuxt");
</script>

<template>
    <div>
        {{ hoge }}
    </div>
</template>

