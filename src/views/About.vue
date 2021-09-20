<template>
  <div class="about">
    <h1>This is an about page</h1>
    <div class="appform">
      <Tamu myapp="Starbhak"/>
    </div>
  </div>
</template>
<script>
import Tamu from "../components/Tamu.vue";
export default {
    nama:"appform",
    components:{
      Tamu,
    }
  }
</script>