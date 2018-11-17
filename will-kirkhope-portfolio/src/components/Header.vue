<template>
  <div class="headerImg">
    <div class="nametag">
      <span class='name'>Will Kirkhope</span>
    </div>
    <div class="DwnArrow bounce">
      <img src="../assets/downArrow.png" alt="">
    </div>
  </div>
</template>


<script>
  export default {
    name: 'Header'
  }
</script>


<style scoped>

.headerImg {
    background-image: url("../assets/HeadImg.jpg");
    height: 60vw;
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

.DwnArrow{
  margin-top: 22vw;
  margin-left: .8vw;
}

.bounce {
  animation: bounce 2s infinite;
}

@keyframes bounce {
  0%, 20%, 50%, 80%, 100% {
    transform: translateY(0);
  }
  40% {
    transform: translateY(-30px);
  }
  60% {
    transform: translateY(-15px);
  }
}

</style>
