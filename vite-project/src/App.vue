<script>
export default {
  data() {
    return {
      title: "La mia prima app con Vite!",
    };
  },
};
</script>

<template>
  <main>
    <h1>{{ title }}</h1>
  </main>
</template>

<style>
main {
  background-color: black;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
h1 {
  text-align: center;
  font-size: 3rem;
  font-family: Arial, Helvetica, sans-serif;
  color: blueviolet;
}
</style>
