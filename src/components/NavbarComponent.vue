<template>
  <div class="navbar">
    <div class="Logo">
      <img src="#" alt="Logo">
    </div>
    <div class="counter">
      Counter: {{count}}<br>
      {{warning()}}
    </div>
    <div class="ButtonsComponents">
      <div class="ComponenteA" @click="increment()"><router-link to="/containerA">Componente A</router-link></div>
      <div class="ComponenteB" @click="increment()"><router-link to="/containerB">Componente B</router-link></div>
      <div class="ComponenteC" @click="increment()"><router-link to="/containerC">Componente C</router-link></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NavbarComponent',
  data(){
    return {
      count: 0,
    }
  },
  methods:{
    increment(){
      return this.count++;
    },
    warning(){
      if(this.count===3){
        return "Alle Comps angeklickt."
      } else if(this.count===4){
        this.count = 1;
      }
    }
  }
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
  font-size: 13pt;
  padding-top: 7px;
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
  display: flex;
  margin-top: 2px;
  margin-right: 10px;
}

.ComponenteA{
  width: 120px;
  height: 50px;
  margin-left: 5px;
  padding-top: 14px;
  font-size: 14px;
  text-align: center;
  font-family: Arial, sans-serif;
  border-radius: 6px;
  border: 2px solid black;
  background-color: white;
}

.ComponenteA a{
  color: black;
  text-decoration: none;
}

.ComponenteB{
  width: 120px;
  height: 50px;
  margin-left: 5px;
  padding-top: 14px;
  font-size: 14px;
  text-align: center;
  color: black;
  text-decoration: none;
  font-family: Arial, sans-serif;
  border-radius: 6px;
  border: 2px solid black;
  background-color: white;
}

.ComponenteB a{
  color: black;
  text-decoration: none;
}

.ComponenteC a{
  color: black;
  text-decoration: none;
}

.ComponenteC{
  width: 120px;
  height: 50px;
  margin-left: 5px;
  padding-top: 14px;
  font-size: 14px;
  text-align: center;
  color: black;
  text-decoration: none;
  font-family: Arial, sans-serif;
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
