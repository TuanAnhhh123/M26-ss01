<template>
  <div class="user-layout">
    <header-component />
    <navbar-component />
    <div class="content">
      <menu-component />
      <main-component />
      <article-component />
    </div>
    <footer-component />
  </div>
</template>

<script>
import HeaderComponent from './Header1.vue';
import NavbarComponent from './Navbar.vue';
import MenuComponent from './Menu1.vue';
import MainComponent from './Main1.vue';
import ArticleComponent from './Article.vue';

export default {
  name: "UserLayout",
  components: {
    HeaderComponent,
    NavbarComponent,
    MenuComponent,
    MainComponent,
    ArticleComponent
  }
};
</script>

<style scoped>
.user-layout {
  display: flex;
  flex-direction: column;
  height: 100vh;
}

header-component {
  flex-shrink: 0;
}

navbar-component {
  flex-shrink: 0;
}

.content {
  display: flex;
  flex-grow: 1;
}

menu-component {
  width: 15%;
}

main-component {
  width: 70%;
  padding: 10px;
}

article-component {
  width: 15%;
}
</style>
