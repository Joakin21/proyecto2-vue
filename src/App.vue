<template>
  <div id="app">
    <Header />
    <MyTable />
  </div>
</template>

<script>

import MyTable from './components/MyTable.vue'
import Header from './components/Header.vue'

export default {
  name: 'App',
  components: {
    Header,
    MyTable
  }
}
</script>

<style>
/*
#app {

}
*/
</style>
