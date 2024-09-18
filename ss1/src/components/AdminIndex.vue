<template>
  <div class="admin-layout">
    <header-component />
    <div class="content">
      <menu-component />
      <main-component />
    </div>
    <footer-component />
  </div>
</template>

<script>
import HeaderComponent from './Dau.vue';
import MenuComponent from './Menu.vue';
import MainComponent from './Main.vue';
import FooterComponent from './Footer.vue';

export default {
  name: "AdminIndex",
  components: {
    HeaderComponent,
    MenuComponent,
    MainComponent,
    FooterComponent,
  },
};
</script>

<style scoped>
.admin-layout {
  display: flex;
  flex-direction: column;
  height: 100vh;
}

header-component {
  flex-shrink: 0;
}

footer-component {
  flex-shrink: 0;
}

.content {
  display: flex;
  flex-grow: 1;
}

menu-component {
  width: 20%;
}

main-component {
  width: 80%;
}
</style>
