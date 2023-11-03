<template>
    <img src="./static/home.png" width="50" height="50" />
    <Hello />
</template>

<script>
import { defineComponent } from 'vue';

import Hello from './Hello.vue';

export default defineComponent({
    name: 'App',
    components: {
        Hello
    }
});

</script>

<style scoped>
h1 {
    width: 100%;
    text-align: center;
    margin-top: 10px;
}

img {
    display: block;
    margin: auto;
}
</style>