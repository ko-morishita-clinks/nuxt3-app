<template>
  <div class="container">
    <slot />
    <footer>&copy; proglus.jp</footer>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.container {
  color: red;
}

footer {
  background-color: orange;
  color: white;
  text-align: center;
}

html {
  font-family: "Permanent Marker", cursive;
  font-weight: 400;
  font-style: normal;
}
</style>