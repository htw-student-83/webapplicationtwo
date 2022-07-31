<template>
  <div class="container">
    <p>Component A</p>
  </div>
</template>

<script>
export default {
  name: 'ComponentOne',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container{
  height: 100vh;
  width: 100%;
  background-color: lightskyblue;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 65px;
}
</style>
