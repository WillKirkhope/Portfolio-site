<template lang="html">
  <div class="skills-cards">
    <h1> Developer Skills</h1>
  <div class="skills-logo1">
    <img src="../assets/vue.png" alt="Vue.js" class="grayscale">
    <img src="../assets/React.png" alt="React.js" class="grayscale">
    <img src="../assets/nodejs.png" alt="Node.js" class="grayscale">
  </div>
  <div class="skills-logo2">
    <img src="../assets/PostgreSQL.png" alt="PostgreSQL" class="grayscale">
    <img src="../assets/heroku.png" alt="Heroku" class="grayscale">
    <img src="../assets/firebase.png" alt="Firebase" class="grayscale">
  </div>
  <div class="skills-logo3">
    <img src="../assets/knex.png" alt="Knex" class="grayscale">
    <img src="../assets/cypress.png" alt="Cypress.io" class="grayscale">
    <img src="../assets/html5.png" alt="HTML5" class="grayscale">
  </div>
  <div class="skills-logo4">
    <img src="../assets/Css3.png" alt="CSS3" class="grayscale">
    <img src="../assets/JavaScript-logo.png" alt="JavaScript" class="grayscale">
    <img src="../assets/github.png" alt="Github" class="grayscale">
  </div>
      <div class="text">
        <p>And Many More!</p>
      </div>
  </div>
</template>

<script>
export default {
  name: 'Skills'
}
</script>

<style lang="css">

.skills-cards{
  display: flex;
  flex-direction: column;
  margin: 5vw 10vw;
  z-index: 2;
}

.grayscale {
  filter: grayscale(100%);
}

.skills-logo1{
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  margin-bottom: 2vw;
}

.skills-logo2{
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  margin-bottom: 2vw;
}

.skills-logo3{
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  margin-bottom: 2vw;
}

.skills-logo4{
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  margin-bottom: 2vw;
}

h1{
  text-decoration: underline;
}

.text{
  font-size: 24px;
}

img{
  height: 10vw;
  width: 10vw;
  padding-bottom: 2vw;
}
</style>
