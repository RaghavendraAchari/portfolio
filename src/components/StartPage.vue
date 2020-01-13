<template>
  <div class="container-fluid">
    <NavBar/>
    <Info/>
    <hr  class="container my-4">
    <Grad />
  </div>
</template>

<script>

import NavBar from "./NavBar.vue";
import Info from "./Info.vue";
import Grad from "./Grad";

export default {
  name: "StartPage",
  props: {
    msg: String
  },
  components:{
    NavBar,
    Info,
    Grad
  }
};
</script>
