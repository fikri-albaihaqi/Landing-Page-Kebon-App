<template>
  <div class="navigation">
    <img id="logo" src="../assets/Logo.png" alt="">
    <ul>
      <li>Home</li>
      <li>Fitur</li>
      <li>Kontak</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Navigation",
};
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Kanit&display=swap');

.navigation {
  width: 100vw;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0px 100px;
  position: fixed;
  margin-top: 50px;
}

#logo {
  width: 150px;
}

.navigation ul {
  display: flex;
  align-items: center;
  justify-content: center;
}

.navigation ul li {
  list-style: none;
  padding: 20px;
  font-family: 'Kanit', sans-serif;
  font-size: 24px;
  color: white;
}
</style>
