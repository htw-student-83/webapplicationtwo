<template>
  <NavbarComponent/>
  <ComponentOne/>
  <ComponentTwo/>
  <ComponentThree/>
</template>

<script>
import ComponentOne from './components/ComponentOne.vue'
import ComponentTwo from './components/ComponentTwo.vue'
import ComponentThree from './components/ComponentThree.vue'
import NavbarComponent from './components/NavbarComponent.vue'

export default {
  name: 'App',
  components: {
    ComponentOne,
    ComponentTwo,
    ComponentThree,
    NavbarComponent
  }
}
</script>

<style>
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
</style>
