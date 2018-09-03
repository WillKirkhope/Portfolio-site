<template lang="html">
  <div class="Proj-container">
    <div class="backgroundImg2">

    </div>
    <h1>Projects</h1>
    <div class="project1">
      <h3>The Borough</h3>
      <p>The Borough was an app created initially as a student project with a timeline of four days and the challenge of learning a new framework on top of that. The app is a meetup app geared towards getting community service events started and bringing knowledge about them to more people.</p>
      <p>Tech Used: HTML, CSS, Bootstrap, VueJS, Heroku, PostgreSQL, Knex, Express, Git/Github, GoogleMaps</p>
      <img src="" alt="">
    </div>
    <div class="project2">
      <h3>Dormistorë</h3>
      <p>Dormistore is a simple CRUD app designed to be an Admin side of a dorm/apartment storefront site, the admin has access to all the products, the can add more, and edit the amount of product they have, as well and delete sold out items. Future implementations coming soon!</p>
      <p>Tech Used: CSS, HTML, React, Knex, Heroku, PostgreSQL, Firebase, Express</p>
      <img src="" alt="">
    </div>
    <div class="project3">
      <h3>This Site</h3>
      <p></p>
      <img src="" alt="">
    </div>
    <div class="project4">
      <h3>Pokémon Team Selector</h3>
      <p></p>
      <img src="" alt="">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Projects'
}
</script>

<style lang="css">

.backgroundImg2 {
    background-image: url("../assets/Code.png");
    height: 38vw;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

</style>
