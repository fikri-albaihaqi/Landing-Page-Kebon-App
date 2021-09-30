<template>
  <div class="container">
    <div class="card-download">
      <h1>Mulai Menanam Dengan Kami!</h1>
      <div class="download-button">
        <a href=""><img src="../assets/play-store-download.png" alt=""></a>
        <a href=""><img src="../assets/app-store-download.png" alt=""></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Download'
}
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Kanit&display=swap");

.container {
  width: 45%;
  margin: auto;
  margin-top: 80px;
  margin-bottom: 80px;
}

.card-download {
  border-radius: 20px;
  box-shadow: 0px 8px 24px rgba(0, 0, 0, 0.15);
  padding: 32px;
}

h1 {
  font-family: 'Kanit', sans-serif;
  font-size: 36px;
  text-align: center;
}

.download-button {
  display: flex;
  justify-content: center;
  align-content: center;
}

.download-button a {
  margin: 16px;
}
</style>