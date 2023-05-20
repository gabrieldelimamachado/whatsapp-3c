<template>
  <main class="columns id-multiline">
     <div class="column is-one-quarter">
      <SideBar />
     </div>
     <div class="column is-three-threequarter">
      <ChatExample />
     </div>
     <div class="column is-three-threequarter">
      <FullBody />
     </div>
     <div class="column is-three-threequarter">
      <ButtonAccess />
     </div>
     <div class="column is-three-threequarter">
     <FooterBar />
     </div>
  </main>
  
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import SideBar from './components/SideBar.vue'
import ChatExample from './components/ChatExample.vue'
import FullBody from  './components/FullBody.vue'
import ButtonAccess from './components/ButtonAccess.vue'
import FooterBar from './components/FooterBar.vue'


export default defineComponent({
  name: 'App',
  components: {
    SideBar,
    ChatExample,
    FullBody,
    ButtonAccess,
    FooterBar
  }
});
</script>
<style>

</style>
