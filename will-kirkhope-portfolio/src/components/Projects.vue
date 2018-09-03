<template lang="html">
  <div class="Proj-container">
    <div class="backgroundImg2">

    </div>
    <h1>Projects</h1>
    <div class="project">
      <h3>The Borough</h3>
      <p>The Borough was an app created initially as a student project with a timeline of four days and the challenge of learning a new framework on top of that. The app is a meetup app geared towards getting community service events started and bringing knowledge about them to more people.</p>
      <p>Tech Used: HTML, CSS, JavaScript, Bootstrap, Firebase, VueJS, Heroku, PostgreSQL, Knex, Express, Git/Github, GoogleMaps</p>
      <img src="../assets/TheBorough.png" alt="">
    </div>
    <div class="project">
      <h3>Dormistorë</h3>
      <p>Dormistore is a simple CRUD app designed to be an Admin side of a dorm/apartment storefront site, the admin has access to all the products, the can add more, and edit the amount of product they have, as well and delete sold out items. Future implementations coming soon!</p>
      <p>Tech Used: CSS, HTML, JavaScript, React, Knex, Heroku, PostgreSQL, Firebase, Express</p>
      <img src="../assets/dormistore.png" alt="">
    </div>
    <div class="project">
      <h3>This Site</h3>
      <p>A clean simple portfolio site</p>
      <p>Tech Used: VueJS, Bootstrap, CSS, HTML, JavaScript, Firebase</p>
      <img src="../assets/personal.png" alt="">
    </div>
    <div class="project">
      <h3>Pokémon Team Selector</h3>
      <p>Ever wanted to see what your ideal Pokémon Team is, or compare it to a friends, or do you know a Pokémon name but don't know how it looks? Well Pokémon Team Selector is for you! This is a fun little app to help you visualize your very own Pokémon Team!</p>
      <p>Tech Used: JavaScript, CSS, HTML, Firebase</p>
      <img src="../assets/pokemon.png" alt="">
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
