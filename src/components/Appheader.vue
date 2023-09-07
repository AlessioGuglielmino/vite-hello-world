<script>
export default {
  data() {
    return {
      links: ["link 1 ", "link 2 ", "link 3 "],
    };
  },
};
</script>

<template>
  <ul>
    <li v-for="link in links">
      {{ link }}
    </li>
  </ul>
</template>

<style>
li {
  color: white;
  display: inline-block;
}
</style>
