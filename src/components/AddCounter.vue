<script>
export default {
    methods: {
        AddCounter() {
            alert('clicked');
        },
    },
};
</script>

<template>
    <h1 class="title">Contadores</h1>
    <button @click="AddCounter" class="buttonNewCounter">+</button>
</template>

<style scoped>
.title {
    color: #FFF;
    font-size: 1.3em;
    text-transform: uppercase;
}

.buttonNewCounter {
    background-color: #BAEDA9;
    border-radius: 10px;
    border: 0;
    font-size: 2em;
}
</style>