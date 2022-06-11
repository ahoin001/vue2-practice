<template>

<div class="container">
  <h1> Hey There! I am the {{name}} component</h1>
  <p>I am some statically rendered data. <em>BUT</em></p>
  <p>I have a dynamically provided message:</p>
  <p>{{alexMessage}}</p>
</div>

</template>

<script>
export default {
  name: "alexComponent",
  props: {
    alexMessage : String,
    name: String
  }
}
</script>

<style scoped>
.container {
  padding: 1rem;
  border: solid 1px gold;
}
</style>
