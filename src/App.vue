<template>
  <NavbarComponent/>
  <router-view/>
</template>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

</style>

<script>

import NavbarComponent from "@/components/NavbarComponent";
export default {
  components: {
    NavbarComponent
  },
  methods:{
    increment(){
      this.count++;
    }
  }
}
</script>