<template>
  <div class="app">
    <h1>Hello Vue3</h1>
    <Person1/>
    <Person2/>
    <Car1/>
    <Car2/>
  </div>
</template>

<script lang='js'>
import Person1 from "./components/1_import_component.vue"
import Person2 from "./components/2_declarative_rendering_ref.vue"
import Car1 from "./components/2_declarative_rendering_reactive.vue"
import Car2 from "./components/2_declarative_rendering_ref_object.vue"

export default {
  name: "App",
  components: {Person1, Person2, Car1, Car2}
}
</script>

<style scoped>
.app {
  background-color: #ddd;
  box-shadow: 0 0 10px;
  border-radius: 10px;
  padding: 20px;
}
</style>