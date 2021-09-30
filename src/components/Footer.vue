<template>
  <div class="container">
    <img src="../assets/Logo.png" alt="" />
    <p>Copyright &copy; 2021</p>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Nunito&display=swap");

.container {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  background-color: #67C57B;
  font-family: 'Nunito';
  font-size: 18px;
  color: white;
  padding: 88px;
}

.container img {
  margin-bottom: 16px;
}
</style>
