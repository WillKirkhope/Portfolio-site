<template>
  <div class="headerImg">
    <div class="nametag">
      <span class='name'>Will Kirkhope</span>
    </div>
  </div>
  <!-- <header class="header">

    <h1 class = "header-title">Will Kirkhope</h1>
  </header> -->
</template>


<script>
  export default {
    name: 'Header'
  }
</script>


<style scoped>

.headerImg {
    /* The image used */
    background-image: url("../assets/HeadImg.jpg");

    /* Set a specific height */
    height: 60vw;

    /* Create the parallax scrolling effect */
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

.name{
  background-color: #111;
  color: #fff;
  padding: 20px;
  font-size: 36px;
  letter-spacing: 10px;
  justify-content: center;
  text-align: center;
  opacity: 0.65;
}

.nametag{
  padding-top: 20vw;
}

  /* .header {
    box-sizing:border-box;
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    height: 8vw;
    padding: 0 10vw;
    background-color: #2C4251;
    padding-top:5px;
    color: #C1C1C1;
    position: fixed;
    z-index: 1;
  }
  .nav-links a {
    padding: .5vw;
    color: #C1C1C1;
    text-decoration:none;
  }
  #logo-img {
    height: 8vw;
    width:auto;
  }
  .header-title {
    font-size: 40px;
    padding-right:45%;
  } */
</style>
