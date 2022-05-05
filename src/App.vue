<template>
  <div id="app">
    <AppHeader />
    <main>
      <AppGrid />
    </main>
    <footer>
      <AppFooter />
    </footer>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue'
import AppGrid from './components/AppGrid.vue'
import AppFooter from './components/AppFooter.vue'
// import axios from 'axios'

export default {
  name: 'App',
  components: {
    AppHeader,
    AppGrid,
    AppFooter,
  },
  // mounted(){
  //   axios.get('https://flynn.boolean.careers/exercises/api/random/name').then((res)=>{
  //     console.log(res.data)
  //   })
  // }
}
</script>

<style lang="scss">
@import './style/variables';
@import './style/generals';
@import "./style/utilities";
h1,
h2,
h3,
h4,
h5,
h6 {
    color: $primary;
}
</style>
