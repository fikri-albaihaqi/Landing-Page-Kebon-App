<template>
  <div class="header">
    <div class="container">
      <div class="left-side">
        <h1>Lorem Ipsum</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus at quam imperdiet, commodo augue sed, ornare turpis.</p>
        <a href=""><img src="../assets/play-store-download.png" alt=""></a>
        <a href=""><img src="../assets/app-store-download.png" alt=""></a>
      </div>

      <div class="right-side">
        <img src="../assets/google-pixel-2.png" alt="">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Kanit&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Nunito&display=swap');

.header {
  height: 100vh;
  background-image: url("../assets/bg-header.png");
  background-size: cover;
  background-repeat: no-repeat;
}

.container {
  width: 80%;
  height: 100vh;
  margin: auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.left-side {
  width: 50%;
}

.left-side h1 {
  color: white;
  font-family: 'Kanit', sans-serif;
  font-size: 48px;
  font-weight: 600;
}

.left-side p {
  color: white;
  font-family: 'Nunito', sans-serif;
  font-size: 18px;
}

.left-side img {
  margin-top: 20px;
  margin-right: 20px;
}

.right-side {
  width: 30%;
}
</style>