<template>
  
  <div>
    <h3 class="mb-3 text-center">{{title_mytable}}</h3>

    <b-table striped hover :items="items"></b-table>
      
  </div>
 
</template>

<script>
export default {
  name:"MyTable",
  data() {
    return {
      title_mytable:"Alumnos",
      items: [
          {age:23, first_name:"Carlos", last_name:"Navarro"},
          {age:21, first_name:"Larsen", last_name:"Shaw"},
          {age:89, first_name:"Geneva", last_name:"Wilson"},
          {age:12, first_name:"Jami", last_name:"Carney"},
      ]
    }
  },
  methods: {
    saludar: function(){
      alert("Hola :)")
    }
  }
}
</script>

<style scoped>


</style>