<template>
  <div class="container">
    <NavBar/>
    <Info/>
  </div>
</template>

<script>

import NavBar from "./NavBar.vue";
import Info from "./Info.vue";

export default {
  name: "StartPage",
  props: {
    msg: String
  },
  components:{
    NavBar,
    Info
  }
};
</script>
