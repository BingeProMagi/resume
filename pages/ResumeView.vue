<template>
  <v-layout column justify-center align-center>
    <v-flex xs24 sm24 md24 class="content">
      <v-flex xs12 sm24 md24 class="headline">
        <h2>MARKUS PANTZAR</h2>
        <span>WEBBUTVECKLARE</span>
        <img src="/static/markus.png" alt="markus-resume"/>
      </v-flex>
      <v-flex xs12 sm6 md6 class="experience">
        <h3>ERFARENHET</h3>
        <h4>Hauschild + Siegel</h4>
        <p>Ansvar över utveckling och uppdateringar av nybyggnations-hemsidor i WordPress.</p>
        <span>2017 - Nuvarande</span>

        <h4>Great Agency</h4>
        <p>Byggde komponenter till Great Agencys egna hemsida, layout-mall till framtida hemsidor. Utvecklade i E-commerce CMS:et Shopify.</p>
        <span>2017 - 10 veckor - Praktik</span>

        <h3 class="skills-head">Skills</h3>
        <p class="skills">HTML  CSS  JavaScript  PHP  MySQL  WordPress</p> 
        <p class="skills"> Drupal
        Vue.js JQuery SASS Laravel NPM Gulp </p>
        <p class="skills last">Git Agila Metoder</p>
      </v-flex>

      <v-flex xs12 sm6 md6 class="education">
        <h3>UTBILDNING</h3>
        <h4>Medieinstitutet</h4>
        <p>Webbutveckling med inriktning på Content Management Systems</p>
        <span>2016 - 2018</span>

        <h4>Linneuniversitetet</h4>
        <p>Teknisktbasår</p>
        <span>2011 - 2012</span>

        <h4>Ållebergsgymnasiet</h4>
        <p>Industriella Programmet</p>
        <span>2004 - 2007</span>

        <h3>Övrigt</h3>
        <ul>
          <li>Ungdomstränare, IFK Falköping</li>
          <li>Ishockeydomare upp till åldrarna 16</li>
        </ul>

      </v-flex>
      <v-flex xs12 sm24 md24 class="headline-reference">
        <h3>REFERENSER</h3>
      </v-flex>
      <v-flex xs12 sm24 md24 class="reference">
        <div>
          <h4>Jonas Egidius</h4>
          <span>COO / Developer</span>
          <ul>
            <li>Telefon: 040 - 608 66 65</li>
            <li>Mail: jonas.egidius@greatagency.se</li>
          </ul>
        </div>
        <div>
          <h4>Cord Siegel</h4>
          <span>Delägare, Hauschild + Siegel</span>
          <ul>
            <li>Telefon: +46 735 23 90 01</li>
            <li>Mail: cord@hauschild-siegel.com</li>
          </ul>
        </div>
      </v-flex>
    </v-flex>
  </v-layout>
</template>
<style>
  .skills {
    font-weight: 500;
    margin-bottom: 5px;
  }
  .headline-reference {
    border-top: 1px solid #656464;
    text-align: center;
    margin: 0 100px;

  }
  .reference {
  
  margin: 0 100px;
  text-align: center;
  margin-bottom: 40px;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-evenly;
  }
  .reference li {
    list-style: none;
  }
  .reference div {
    margin-top: 20px;
  }
  .headline-reference h3 {
    margin-top: 20px;
  }
  .headline {
    text-align: center;
    margin-bottom: 20px;
  }
  .headline h2 {
    margin-top: 40px;
    margin-bottom: 10px;
  }
  .content {
    flex-wrap: wrap;
    display: flex;
  }
  .headline img {
    width: 200px;
    display: flex;
    margin: 0 auto;
    margin-top: 20px;
  }
  .experience {
    text-align: right;
    padding-right: 25px;
  }
  .experience h3.skills-head  {
    margin-top: 20px;
  }
  .experience p {
    margin-left: 150px;
    margin-bottom: 3px;
  }
  .experience h3, .education h3 {
    margin-bottom: 15px;
    margin-top: 10px;
  }
  .experience h4, .education h4 {
    margin-top: 15px;
  }
  .experience span, .education span {
    font-style: italic;
    font-size: 12px;
  }
  .education li {
    list-style: none;
    margin-bottom: 5px
  }
  .education {
    padding-left: 25px;
    border-left: 1px solid #656464;
    margin-bottom: 20px;
  }
  .education p {
    margin-right: 150px;
    margin-bottom: 3px;
  }
  .education, .experience {
  }
  @media screen and (max-width: 590px) {
    .experience {
    text-align: left;
    padding-right: 0;
    border-bottom: solid 1px #656464;
    margin: 0 20px;
    }
    .experience p {
      margin-left: 0px;
    }
    .headline-reference {
    margin: 0 20px;
    }
    .last {
      margin-bottom: 25px;
    }
  }
</style>