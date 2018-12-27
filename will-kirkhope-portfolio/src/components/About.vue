<template lang="html">
  <div class="about-me">
    <h1>About Me</h1>
    <div class="info">
      <p>
        Hard work beats talent when talent fails to work hard. Working hard is what I do best, whether it's in the gym or in front of the computer, I take pride in being one of the hardest workers in the room.
        Making a career transition from the Fitness Industry to Web Development, I have been devloping for about a year now, and I have a ton of fun with Programming and Frontend Development as well as Server-Side Programming and Single Page Applications.
      </p>
      <p>
        I am a recent graduate of the Web Development Immersive program at Galvanize. I've always loved building things from scratch and problem solving is second nature for me! I am currently looking for employment opportunities in the Greater Denver / Boulder area.
      </p>
      <p>
        In my free time I like to get my adrenaline fix, riding motorcycles, rock climbing, mountaineering, and a ton of other extreme sports! I spend to much time in the gym and I am probably better than you at video games...
      </p>
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

.info {
  padding-left: 5vw;
  padding-right: 5vw;
}

.about-me{
  padding-top: 2vw;
}

.backgroundImg {
    background-image: url("../assets/picture.jpg");
    height: 38vw;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

</style>
