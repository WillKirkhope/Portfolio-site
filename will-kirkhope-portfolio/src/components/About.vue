<template lang="html">
  <div class="about-me">
    <div class="info">
    <p>Hard work beats talent when talent fails to work hard. Working hard is what I do best, whether it's in the gym or in front of the computer, I take pride in being one of the hardest workers in the room.
Making a brave career transition from the Fitness Industry to Web Development, I started at Galvanize this April and I have a ton of fun with Programming and Frontend Development as well as Server-Side Programming and Single page Applications. I hold multiple certifications in the Fitness Industry, and started my own Private Training Business as well as running a functional Online Training site.

I am currently enrolled in the Web Development Immersive program at Galvanize. I've always loved building things from scratch and problem solving is second nature for me! In the coming months I will be looking for employment opportunities in the Greater Denver / Boulder area. I would love to work for a company that is involved in the fitness or outdoor industry as I feel that I would be an invaluable member due to my previous experience.

In my free time I like to get my adrenaline fix, riding motorcycles, rock climbing, mountaineering, and a ton of other extreme sports! I spend to much time in the gym and I am probably better than you at video games...</p>
    </div>
    <div class="">
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    </div>
    <div class="">
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    </div>
    <div class="backgroundImg">

    </div>
  </div>
</template>

<script>
export default {
  name: 'About'
}
</script>

<style scoped="">
body {
  height: 100vh;
  width: 100%;
}

.about-me{
  padding-top: 2vw;
}

.backgroundImg {
    /* The image used */
    background-image: url("../assets/picture.jpg");

    /* Set a specific height */
    height: 500px;

    /* Create the parallax scrolling effect */
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

</style>
