<template>
  <header>
    <img src="logo.svg" alt="Logo">
    <h1>{{ title }}</h1>
  </header>
</template>

<style>
body {
  margin: 0;
  padding: 0;
}

header {
  height: 100vh;
  width: 100%;
  display: flex;

  background-color: #001e26;
  color: white;
}

header img {
  margin: auto 0 auto auto;
  width: 150px;
}

header h1 {
  margin: auto auto auto 0;
  font-size: 5em;
  font-family: sans-serif;
}
</style>

<script>
export default {
  asyncData() {
    return {
      title: 'Nuxt'
    }
  }
}
</script>
