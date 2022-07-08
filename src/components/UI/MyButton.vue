<template>
    <button class="btn">
        <slot></slot>
    </button>
</template>

<script>
export default {
    name: "my-button"
}
</script>

<style scoped>
.btn {
    color: teal;

    padding: 10px 15px;
    background: none;
    border: 1px solid teal;
}
</style>