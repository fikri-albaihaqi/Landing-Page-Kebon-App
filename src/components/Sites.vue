<template>
  <div class="container">
    <div class="title">
      <h1>Our Sites</h1>
      <p>
        Aliquam tempor nec dui eu tristique. Proin rhoncus eget odio ut <br />
        pharetra. Phasellus mollis eget diam eget viverra.
      </p>
    </div>

    <div class="site-list">
      <Card
        :img="require('@/assets/card-image.png')"
        title="Depari Farm"
        mainText="Sed euismod dapibus congue. Praesent posuere vitae diam sit amet mollis. Vivamus sit amet nunc interdum est tincidunt consequat. Duis volutpat odio at nisl suscipit eleifend."
      />

      <Card
        :img="require('@/assets/card-image.png')"
        title="SeladaSegar"
        mainText="Sed euismod dapibus congue. Praesent posuere vitae diam sit amet mollis. Vivamus sit amet nunc interdum est tincidunt consequat. Duis volutpat odio at nisl suscipit eleifend."
      />

      <Card
        :img="require('@/assets/card-image.png')"
        title="Green HOS"
        mainText="Sed euismod dapibus congue. Praesent posuere vitae diam sit amet mollis. Vivamus sit amet nunc interdum est tincidunt consequat. Duis volutpat odio at nisl suscipit eleifend."
      />
    </div>
  </div>
</template>

<script>
import Card from "./Card.vue";

export default {
  name: "Sites",
  components: {
    Card,
  },
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Kanit&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Nunito&display=swap");

.container {
  width: 80%;
  margin: auto;
  margin-top: 100px;
  margin-bottom: 100px;
}

.title h1 {
  font-family: "Kanit", sans-serif;
  font-size: 48px;
  text-align: center;
}

.title p {
  font-family: "Nunito", sans-serif;
  color: #ababab;
  font-size: 24px;
  text-align: center;
  margin-top: 16px;
}

.site-list {
  display: flex;
  justify-content: center;
  align-content: center;
}

.card {
  margin: 64px 32px 0px 32px;
  box-shadow: 0px 8px 24px rgba(0, 0, 0, 0.15);
}

:deep(.card) {
  width: 350px;
  border-radius: 10px;
  text-align: center;
}

:deep(.card) img {
  border-radius: 10px 10px 0px 0px;
  width: 350px;
}

:deep(.card) h1 {
  font-family: 'Nunito', sans-serif;
  font-size: 18px;
  font-weight: 700;
  padding: 24px 0px 8px 0px;
}

:deep(.card) p {
  font-family: 'Nunito', sans-serif;
  font-size: 14px;
  padding: 0px 24px 40px 24px;
  color: #ABABAB;
}
</style>
