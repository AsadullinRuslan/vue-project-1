<script setup></script>

<template>
    <button class="button">
    <div>
        <slot name="blue" />
    </div>
        <slot />
    </button>
</template>

<style scoped>
    .button {
        background: var(--gradient);
        padding: 10px 20px;
        font-family: var( --font);
        border: none;
        border-radius: 10px;
        font-size: 20px;
        font-weight: 600;
        color: var(--primary);
        cursor: pointer;
        transition: .3s;
    }
    .button:hover {
        background: var(--gradient-inverted);
    }
</style>