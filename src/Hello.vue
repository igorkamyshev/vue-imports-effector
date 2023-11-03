<script>
import { createStore } from 'effector'
import { useStore } from 'effector-vue/composition'

const $s = createStore('Hello, World!')

export default {
    setup() {
        const s = useStore($s)
        return { s }
    }
};
</script>

<template>
    <h1>{{ s }}</h1>
</template>