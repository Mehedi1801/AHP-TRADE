<template>
  <div id="app">
    <div id="nav">
      <Header></Header>
      <Sidebar></Sidebar>
      <router-view/>
      <Footer></Footer>
    </div>
    
  </div>
</template>
<script>
import Header from "./layout/Header" 
import Sidebar from "./layout/Sidebar" 
import Footer from "./layout/Footer"
export default {
  components:{Header, Sidebar, Footer}
  
}
</script>
<style>

</style>
