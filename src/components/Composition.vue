<template>
    Composition {{ a }}
    <button @click="add">add</button>
</template>
<script>
import { ref } from 'vue';

export default {
    setup(props, ctx) {
        console.log(ctx);
        const a = ref(2);
        return { a }
    },
    data() {
        
    }
}
</script>