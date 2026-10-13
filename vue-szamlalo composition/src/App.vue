<template>
  <div class="app">
    <h1>Vue komponensek gyakorlás</h1>
    <p class="leiras">Az alábbi számláló egy külön <code>.vue</code> fájlban van.</p>

    <Szamlalo />
  </div>
</template>

<script>
import Szamlalo from './components/Szamlalo.vue'

export default {
  name: 'App',
  components: {
    Szamlalo
  }
}
</script>

<style>
.app {
  font-family: Arial, sans-serif;
  max-width: 500px;
  margin: 40px auto;
  padding: 20px;
}
h1 {
  color: #1a1a1a;
}
.leiras {
  color: #666;
  margin-bottom: 24px;
}
code {
  background: #eee;
  padding: 2px 6px;
  border-radius: 4px;
}
</style>