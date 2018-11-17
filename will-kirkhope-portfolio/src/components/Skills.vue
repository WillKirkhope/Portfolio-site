<template lang="html">
  <div class="skills-cards">
    <h1>Skills</h1>
      <b-card-group deck
                    class="mb-3">
          <b-card bg-variant="light"
                  text-variant="black"
                  style="max-width: 30vw;  max-height: 20vw;"
                  header="Vue.js"
                  class="text-center">
                  <img src="../assets/vue.png" alt="">
          </b-card>
          <b-card bg-variant="light"
                  text-variant="black"
                  style="max-width: 30vw; max-height: 20vw;"
                  header="React.js"
                  class="text-center">
                  <img src="../assets/React.png" alt="">
          </b-card>
          <b-card bg-variant="light"
                  text-variant="black"
                  style="max-width: 30vw; max-height: 20vw;"
                  header="Node.js"
                  class="text-center">
              <img src="../assets/nodejs.png" alt="">
          </b-card>
      </b-card-group>
      <b-card-group deck
                    class="mb-3">
          <b-card bg-variant="light"
                  text-variant="black"
                  style="max-width: 30vw; max-height: 20vw;"
                  header="PostgreSQL"
                  class="text-center">
              <img src="../assets/PostgreSQL.png" alt="">
          </b-card>
          <b-card bg-variant="light"
                  text-variant="black"
                  style="max-width: 30vw; max-height: 20vw;"
                  header="Heroku"
                  class="text-center">
              <img src="../assets/heroku.png" alt="">
          </b-card>
          <b-card bg-variant="light"
                  text-variant="black"
                  style="max-width: 30vw; max-height: 20vw;"
                  header="Firebase"
                  class="text-center">
              <img src="../assets/firebase.png" alt="">
          </b-card>
      </b-card-group>
      <b-card-group deck
                    class="mb-3">
          <b-card bg-variant="light"
                  style="max-width: 30vw; max-height: 20vw;"
                  header="Knex"
                  class="text-center">
              <img src="../assets/knex.png" alt="">
          </b-card>
          <b-card bg-variant="light"
                  header="Cypress"
                  text-variant="black"
                  style="max-width: 30vw; max-height: 20vw;"
                  class="text-center">
              <img src="../assets/cypress.png" alt="">
          </b-card>
          <b-card bg-variant="light"
                  header="HTML"
                  text-variant="black"
                  style="max-width: 30vw; max-height: 20vw;"
                  class="text-center">
              <img src="../assets/html5.png" alt="">
          </b-card>
      </b-card-group>
      <b-card-group deck
                    class="mb-3">
          <b-card bg-variant="light"
                  style="max-width: 30vw; max-height: 20vw;"
                  header="CSS"
                  text-variant="black"
                  class="text-center">
              <img src="../assets/Css3.png" alt="">
          </b-card>
          <b-card bg-variant="light"
                  header="JavaScript"
                  text-variant="black"
                  style="max-width: 30vw; max-height: 20vw;"
                  class="text-center">
              <img src="../assets/JavaScript-logo.png" alt="">
          </b-card>
          <b-card bg-variant="light"
                  header="GitHub"
                  text-variant="black"
                  style="max-width: 30vw; max-height: 20vw;"
                  class="text-center">
              <img src="../assets/github.png" alt="">
          </b-card>
      </b-card-group>
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

.text{
  font-size: 24px;
}

img{
  height: 10vw;
  width: 10vw;
  padding-bottom: 2vw;
}
</style>
