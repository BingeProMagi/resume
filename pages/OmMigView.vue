<template>
  <v-layout coloumn>
    <v-flex xs12 sm12 md8>
      <img src="https://source.unsplash.com/random/450x500" alt="Markus"/>
    </v-flex>
    <v-flex xs12 sm12 md16 justify-center align-center class="introduktion">
      <div justify-center align-center>
        <span>Hej, Jag heter</span>
        <h1>Markus Pantzar</h1>
        <p>och är Webbutvecklare specialiserad på front-end.</p>
        <v-btn router :to="adress" outline color="indigo">Kontakta Mig</v-btn>
      </div>
    </v-flex>
    <v-flex
  </v-layout>
</template>
<style type="text/css">
  .introduktion {
    padding: 20px 10vw;
    display: flex;
    justify-content: center;
  }
  .introduktion span {
    font-size: 18px
  }
  .introduktion h1 {
    font-size: 36px
  }
  .introduktion .btn {
    margin: 30px 0;
  }
</style>
<script>
  export default {
    data () {
      return {
        adress: '/kontakt'
      }
    }
  }
</script>
