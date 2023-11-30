<template>
  <header>
    <Navbar />
  </header>
  <main>
    <router-view />
  </main>
  <!-- <footer>
    <p class="mb-5 pb-1 fw-bold">Powered by Altrnt Solutions</p>
  </footer> -->

  <ModalComponent id="exampleModal">
    <template #header>
      
    </template>
    <template #body>
      <MenuComponent />
    </template>
  </ModalComponent>

  <ModalComponent id="tarotModal">
    <template #header>
      
    </template>
    <template #body>
      <TarotInfo />
    </template>
  </ModalComponent>

</template>

<script>
import { computed } from 'vue'
import { AppState } from './AppState'
import Navbar from './components/Navbar.vue'
import ModalComponent from "./components/ModalComponent.vue"

export default {
  setup() {
    return {
      appState: computed(() => AppState)
    }
  },
  components: { Navbar, ModalComponent }
}
</script>
<style lang="scss">
@import "./assets/scss/main.scss";

:root{
  --main-height: calc(100vh - 32px - 64px);
}


footer {
  display: grid;
  place-content: center;
  height: 32px;
}
</style>
