<script>
import Header from './components/Header.vue';
import NotHeader from './components/NotHeader.vue'

export default {
    name: 'App',
    components:{
      Header,
      NotHeader
    }
}
</script>

<template>
  <header>
    <Header />
  </header>
  <div>
    <NotHeader />
  </div>
  <HelloWorld msg="Vite + Vue" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
