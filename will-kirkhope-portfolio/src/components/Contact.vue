<template lang="html">
  <div class="contact-container">
    <div class="backgroundImg3">

    </div>
    <h1>Contact Me</h1>
    <div class="phone">
      <p>Phone: (303)-653-3428</p>
    </div>
    <div class="email">
      <p>Email: kirkhopetraining@yahoo.com</p>
    </div>
    <div class="resume">
      <a href="https://drive.google.com/open?id=1TL9va4bN-3W3OArMaLMoNtPzyTUz2l8g">View Resume</a>
    </div>
    <div class="github">
      <a href="https://github.com/WillKirkhope">GitHub: WillKirkhope</a>
    </div>
    <div class="linkedin">
      <a href="https://www.linkedin.com/in/william-kirkhope/">Linkedin: Will-Kirkhope</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Contact'
}
</script>

<style lang="css">

.backgroundImg3 {
    background-image: url("../assets/rocks.jpg");
    height: 38vw;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

.phone {
  font-size: 24px;
  color: #2c3e50;
}

.email {
  font-size: 24px;
  color: #2c3e50;
}

.resume {
  padding: 1vw;
}

.resume a{
  font-size: 32px;
}

a {
  font-size: 24px;
  color: #2c3e50;
}

</style>
