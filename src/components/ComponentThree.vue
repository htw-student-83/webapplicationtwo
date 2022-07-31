<template>
  <div class="container">
    <p>Component C</p>
  </div>
</template>

<script>
export default {
  name: 'ComponentThree',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container{
  height: 100vh;
  width: 100%;
  background-color: #eeec9f;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 65px;
  border-radius: 5px;
  border: 2px solid #e8ddad;
}
</style>
