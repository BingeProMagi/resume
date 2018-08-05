<template>
 <v-container> 
  <v-layout row>
    <v-flex xs12 sm12 md6  class="tele">
      <span>tele: <a href="tel:+46763212369">076-321 23 69</a></span>
    </v-flex>
    <v-flex xs12 sm12 md6 class="mail">
      <span>mail: <a href="mailto:markuspantzar@gmail.com">markuspantzar@gmail.com</a></span>
    </v-flex>
  </v-layout>
  <v-layout column>
    <v-flex xs12 sm12 md12 class="links">
      <a href="https://github.com/BingeProMagi">
        <img src="../static/github.svg" alt="Github">
      </a>
    </v-flex>
  </v-layout>
</v-container>
</template>
<style>
  .tele, .mail{
    text-align: center;
    font-size: 24px;
  }
  
</style>
<script>
  export default {
    data () {
      return {
      }
    },
    methods: {
    },
  }
</script>
