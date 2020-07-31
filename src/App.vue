<template>
  <div id="app">
    <header>
      <Navigator />
    </header>
    <main>
      <router-view />
    </main>
  </div>
</template>

<script>
// @ is an alias to /src
import Navigator from "@/components/Navigator.vue";

export default {
  components: {
    Navigator
  }
};
</script>

<style>
html {
  font-size: 18px;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    Ubuntu, "Helvetica Neue", sans-serif;
}
#app {
  text-align: center;
  color: #2c3e50;
  display: flex;
  height: 100vh;
}

header {
  display: flex;
  border: 2px solid red;
  flex: 1 0 auto;
  width: 32.4vw;
  flex-direction: row;
  justify-content: flex-end;
}

main {
  display: flex;
  border: 2px solid blue;
  flex: 1 0 auto;
  width: 67.6vw;
}
</style>
