<template>
  <div class="navbar">
    <div class="Logo">
      <img src="#" alt="Logo">
    </div>
    <div class="counter">Counter: 0</div>
    <div class="ButtonsComponents">
      <button class="ComponenteA">Componente A</button>
      <button class="ComponenteB">Componente B</button>
      <button class="ComponenteC">Componente C</button>
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
  background-color: white;
  display: flex;
  justify-content: space-between;
  padding: 10px;
  border: 2px solid lightgreen;
  border-radius: 4px;
  margin-bottom: 2px;
}

.counter{
  margin-left: 10px;
  margin-right: 10px;
  font-size: 15pt;
  padding-top: 20px;
}

.Logo{
  width: 100px;
  height: 50px;
  margin-left: 2px;
  background-color: blue;
  font-size: 20pt;
  color: white;
  text-align: center;
  padding-top: 7px;
  border-radius: 6px;
  font-family: Arial,sans-serif;
}


.ButtonsComponents button{
  width: 110px;
  height: 50px;
  margin-left: 5px;
  font-size: 11pt;
  font-family: Arial,sans-serif;
  border-radius: 6px;
  border: 2px solid black;
  background-color: white;
}

.ButtonsComponents button:hover{
  cursor: pointer;
}

</style>
