<script setup>
import Button from "./components/Button.vue";
const icon = 'blue';
</script>

<template>
    <Button>
        <template #[icon]>+</template>
        Сохранить
    </Button>
</template>

<style scoped></style>
