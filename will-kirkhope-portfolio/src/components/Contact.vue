<template lang="html">
  <div class="contact-container">
    <div class="backgroundImg3">
    </div>
    <h1>Contact Me</h1>
    <div class="contact-images">
      <div class="phone">
        <img id="phone" src="../assets/phone.png" alt="">
        <p id="pho">(303)-653-3428</p>
      </div>
      <div class="email">
        <img id="email" src="../assets/email.png" alt="">
        <p id="em">willkirkhope@gmail</p>
      </div>
      <div class="resume">
        <img id="resume" src="../assets/resume.png" alt=""><br>
        <a id="res" href="https://drive.google.com/open?id=1TL9va4bN-3W3OArMaLMoNtPzyTUz2l8g" target="_blank">Resume</a>
      </div>
      <div class="github">
        <img id="github" src="../assets/github.png" alt=""><br>
        <a id="git" href="https://github.com/WillKirkhope" target="_blank">WillKirkhope</a>
      </div>
      <div class="linkedin">
        <img id="linkedin" src="../assets/linkedin.png" alt=""><br>
        <a id="link" href="https://www.linkedin.com/in/william-kirkhope/" target="_blank">Will-Kirkhope</a>
      </div>
    </div>
    <!-- <div class="contact-info">
      <div class="pho">
        <p id="pho">(303)-653-3428</p>
      </div>
      <div class="em">
        <p id="em">willkirkhope@gmail</p>
      </div>
      <div class="res">
        <a id="res" href="https://drive.google.com/open?id=1TL9va4bN-3W3OArMaLMoNtPzyTUz2l8g" target="_blank">Resume</a>
      </div>
      <div class="git">
        <a id="git" href="https://github.com/WillKirkhope" target="_blank">WillKirkhope</a>
      </div>
      <div class="link">
        <a id="link" href="https://www.linkedin.com/in/william-kirkhope/" target="_blank">Will-Kirkhope</a>
      </div>
    </div> -->
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

#linkedin{
  height: 6.5vw;
  width: 5vw;
}

#github{
  height: 6vw;
  width: 5vw;
}

#resume{
  height: 6vw;
  width: 5vw;
}

#email{
  height: 6.5vw;
  width: 5vw;
}

#phone{
  height: 6vw;
  width: 5vw;
}

.contact-images{
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: baseline;

}

.contact-info {
  display: flex;
  flex-direction: row;
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

.contact-info{
  display: flex;
  font-size: 24px;
  /* align-items: center; */
  /* justify-content: space-around; */
}

.contact-info href{
  text-decoration: none;
  color: #2c3e50;
}

</style>
