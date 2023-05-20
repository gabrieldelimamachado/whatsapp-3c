<template>
    <header>
        <div class="Logo3C">
            <h1>
            <img src="../assets/logo3c.png" alt="">
            </h1> 
        </div>  
    </header>
    <body>
        <div class="WhatsLogo2">
        <h2>
            <img src="../assets/whatsapplogo.png" alt=""> 
        </h2>
        </div>
        <div class="Whatsapp">
        <p>
            Whatsapp
        </p>
        </div>
        <h3>
            <img src="../assets/indicator.png" alt="">
        </h3>
    </body>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
export default defineComponent({
    name: 'SideBar'
})

</script>

<style scoped>
header {
    position: absolute;
    align-items: center;
    padding-left: 7rem;
    padding-top: 3rem;
    width: 20%;
    height: 126vh;   
}

.Logo3C {
    position: fixed;

}

.WhatsLogo2 {
    position: fixed;
    width: 50px;
    left: 20px;
    top: 163px; 
}

.Whatsapp {
    position: fixed;
    width: 50px;
    left: 3rem;
    top: 159px;
    font-size: 18px
}

h3 {
    position: fixed;
    padding-left: 0px;
    padding-top: 10rem; 

}   



</style>
 