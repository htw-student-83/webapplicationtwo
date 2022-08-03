<template>
  <div class="navbar">
    <div class="Logo">
      <img src="#" alt="Logo">
    </div>
    <div class="counter">Counter: 0</div>
    <div class="ButtonsComponents">
      <button class="ComponenteA"><router-link to="/containerA">Componente A</router-link></button>
      <button class="ComponenteB"><router-link to="/containerB">Componente B</router-link></button>
      <button class="ComponenteC"><router-link to="/containerC">Componente C</router-link></button>
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
  border: 2px solid #6d9a6b;
  border-radius: 4px;
  margin-bottom: 2px;
}

.counter{
  margin-left: 10px;
  margin-right: 10px;
  font-size: 15pt;
  padding-top: 20px;
  font-weight: bold;
  font-family: Arial,Arial, sans-serif;
}

.Logo{
  width: 100px;
  height: 50px;
  margin-left: 2px;
  margin-top: 2px;
  background-color: blue;
  border-radius: 6px;
  text-align: center;
  font-family: Arial,sans-serif;
  font-size: 25px;
  font-weight: bold;
  color: white;
  padding-top: 10px;
}


.ButtonsComponents{
  margin-top: 2px;
}

.ButtonsComponents button{
  width: 112px;
  height: 50px;
  margin-left: 5px;
  font-size: 11pt;
  font-family: Arial,sans-serif;
  border-radius: 6px;
  border: 2px solid black;
  background-color: white;
}

.ComponenteA:hover{
  background-color: lightskyblue;
}

.ComponenteB:hover{
  background-color: #c3eec2;
}

.ComponenteC:hover{
  background-color: #eeec9f;
}

button:hover{
  cursor: pointer;
}

</style>
