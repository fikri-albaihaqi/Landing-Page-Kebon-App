<template>
  <div class="wrapper">
    <div class="container">
      <div class="feature">
        <img src="../assets/lahan.png" alt="" />

        <div class="text">
          <h1>Mulai Sewa Lahan Sekarang!</h1>
          <p>
            Maecenas tristique lacus sit amet arcu mattis posuere. In viverra
            ligula augue, rhoncus rhoncus urna blandit eu.
          </p>
        </div>
      </div>

      <div class="feature">
        <div class="text">
          <h1>Mulai Sewa Lahan Sekarang!</h1>
          <p>
            Maecenas tristique lacus sit amet arcu mattis posuere. In viverra
            ligula augue, rhoncus rhoncus urna blandit eu.
          </p>
        </div>

        <img src="../assets/menanam.png" alt="" />
      </div>

      <div class="feature">
        <img src="../assets/monitor.png" alt="" />

        <div class="text">
          <h1>Mulai Sewa Lahan Sekarang!</h1>
          <p>
            Maecenas tristique lacus sit amet arcu mattis posuere. In viverra
            ligula augue, rhoncus rhoncus urna blandit eu.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Features",
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Kanit&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Nunito&display=swap");

.wrapper {
  background-color: #f6f9fc;
  padding: 50px 0px;
}

.container {
  width: 80%;
  margin: auto;
}

h1 {
  color: #202c44;
  font-size: 36px;
  font-family: "Kanit", sans-serif;
}

p {
  color: #ababab;
  font-family: "Nunito", sans-serif;
  font-size: 24px;
}

.feature {
  display: flex;
  align-content: center;
  justify-content: space-evenly;
  align-items: center;
  margin: 100px 0px;
}

.text {
  width: 30%;
}
</style>
