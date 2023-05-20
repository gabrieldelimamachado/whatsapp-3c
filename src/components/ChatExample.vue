<template>
    <header>
        <h1>
            <img src="../assets/conversations.png" alt="">
        </h1>
    </header>
    <header>
        <h2>
            <img src="../assets/ponteiro.png" alt="">
        </h2>
    </header>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
export default defineComponent({
    name: 'ChatExample'
})

</script>

<style scoped>
header h1{
    position: absolute;
    left: 54rem;
    top: 8rem;
    
}

header h2 {
    position: absolute;
    left: 68rem;
    width: 50px;
    top: 32rem;
}
</style>
