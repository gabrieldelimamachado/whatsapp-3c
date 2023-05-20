<template>
      <div class="btn-box1">
        <a href="#">Quero ter acesso antecipado</a>
      </div>
      <div class="btn-box2">
        <a href="#">Quero ter acesso antecipado</a>
      </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
export default defineComponent({
    name: 'ButtonAccess'
})
</script>

<style scoped> 

.btn-box1  a{
    position: fixed;
    top: 26rem;
    left: 22rem;
    display: inline-flex;
    justify-content: center;
    align-items: center;
    width: 17rem;
    height: 38px;
    background: #3057F2;
    border-radius: 8px;
    font-size: 16px;
    color: #FFFFFF;
    text-decoration: none;
    font-weight: 350px;
    letter-spacing: 1px;
}
.btn-box1 a:hover {
    background-color: #627eed;
    content: '';
    position: fixed;
    top: 26rem;
    left: 22rem;
    width: 17rem;
    height: 38px;
}
.btn-box2 a{
    position: absolute;
    top: 4rem;
    left: 75rem;
    display: inline-flex;
    justify-content: center;
    align-items: center;
    width: 17rem;
    height: 38px;
    background: #3057F2;
    border-radius: 8px;
    font-size: 16px;
    color: #FFFFFF;
    text-decoration: none;
    font-weight: 350px;
    letter-spacing: 1px;
}
.btn-box2 a:hover {
    background-color: #627eed;
    content: '';
    position: absolute;
    top: 4rem;
    left: 75rem;
    width: 17rem;
    height: 38px;
}
</style>
