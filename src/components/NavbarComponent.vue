<template>
  <div class="navbar">
    <div class="Logo">
      <img src="#" alt="Logo">
    </div>
    <div class="ButtonsComponents">
      <button>CompA</button>
      <button>CompB</button>
      <button>CompC</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NavbarComponent',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.navbar{
  background-color: #c3eec2;
  display: flex;
  justify-content: space-between;
  padding: 20px;
}

.Logo{
  width: 100px;
  height: 50px;
  background-color: blue;
  font-size: 20pt;
  color: white;
  text-align: center;
  padding-top: 5px;
}

.ButtonsComponents button{
  width: 120px;
  height: 50px;
  margin-left: 20px;
  font-size: 20pt;
  font-family: Arial,sans-serif;
}

</style>
