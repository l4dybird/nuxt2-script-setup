<template>
    <div class="container">
        <TutorialVue :label="text"/>
    </div>
</template>

<script setup lang="ts">
import { ref } from '@nuxtjs/composition-api';
import TutorialVue from '~/components/Tutorial.vue';
const text = ref<string>("123456789");
</script>
