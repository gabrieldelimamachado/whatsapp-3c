<template>
    <div style="background-color:darkgrey;">
    </div>
    <header>
        <div class="WhatsText">
            <h1>
                Whatsapp 3C+
            </h1>
        </div>
    </header>

    <body>
        <header>
            <div class="WhatsLogo">
                <h1>
                    <img src="../assets/whatsapp.png" alt="">
                </h1>
            </div>
            <div class="Text">
                <p>
                    Quer ter acesso antecipado ao Whatsapp da 3C Plus?
                </p>
            </div>
            <div class="Text2">
                <p>
                    O Whatsapp da 3C Plus está chegando e você pode entrar para a lista de primeiros usuários
                </p>
            </div>
        </header>
    </body>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
export default defineComponent({
    name: 'FullBody'
})
</script>

<style scoped>
@font-face {
    font-family: 'RandomGrotesqueStandardSemibold';
    src: url('../assets/assets-fonts/RG-StandardSemibold.woff'),
        url('../assets/assets-fonts/RG-StandardSemibold.woff2');
        
}

.WhatsText {
    position: absolute;
    width: 250px;
    height: 30px;
    left: 22rem;
    top: 50px;
    font-family: 'RandomGrotesqueStandardSemibold', sans-serif;
    font-size: 32px;
    line-height: 40px;
    color: #12263F;
}

.WhatsLogo {
    position: fixed;
    width: 200rem;
    height: 25rem;
    left: 22rem;
    top: 11rem;
}

body .Text {
    position: fixed;
    right: 65rem;
    width: 25rem;
    height: 20rem;
    left: 22rem;
    top: 15rem;
    font-weight: 400;
    font-size: 32px;
    color: #1B1B2B;
  
    
}

body .Text2 {
    position: fixed;
    right: 75rem;
    width: 385px;
    height: 20rem;
    left: 22rem;
    top: 22rem;
    font-weight: 400;
    font-size: 18px;
    font-style: normal;
    line-height: 22px;
    letter-spacing: -0,02em;
    flex: none;
    order: 1;
    flex-grow: 0; 
}


</style>