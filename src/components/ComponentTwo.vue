<template>
  <div class="container">
    <p>Component B</p>
  </div>
</template>

<script>
export default {
  name: 'ComponentTwo',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container{
  height: 100vh;
  width: 100%;
  background-color: #c3eec2;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 65px;
  border-radius: 5px;
  border: 2px solid #85b983;
  font-weight: bold;
  font-family: Arial, sans-serif;
}
</style>
