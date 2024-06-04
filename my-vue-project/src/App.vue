<template>
  <div id="app">
    <AppHeader />
    <main>
      <h1>Loja VIP de Minecraft</h1>
      <AppCart />
    </main>
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue';
import AppFooter from './components/AppFooter.vue';
import AppCart from './components/AppCart.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    AppFooter,
    AppCart
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
}

main {
  padding: 20px;
}
</style>
