<template>
  <div class="wrapper">
    <div class="container">
      <h1>Why Choose Us</h1>
      <div class="benefits-list">
        <Card
          :img="require('@/assets/label.png')"
          title="Lorem"
          mainText="Nam vel velit ac dolor rhoncus pharetra. Nunc 
                    dignissim diam consectetur, dignissim nibh id, 
                    congue odio."
        />

        <Card
          :img="require('@/assets/product.png')"
          title="Ipsum"
          mainText="Nam vel velit ac dolor rhoncus pharetra. Nunc 
                    dignissim diam consectetur, dignissim nibh id, 
                    congue odio."
        />

        <Card
          :img="require('@/assets/done.png')"
          title="Sit"
          mainText="Nam vel velit ac dolor rhoncus pharetra. Nunc 
                    dignissim diam consectetur, dignissim nibh id, 
                    congue odio."
        />

        <Card
          :img="require('@/assets/antivirus.png')"
          title="Dolor"
          mainText="Nam vel velit ac dolor rhoncus pharetra. Nunc 
                    dignissim diam consectetur, dignissim nibh id, 
                    congue odio."
        />
      </div>
    </div>
  </div>
</template>

<script>
import Card from "./Card.vue";

export default {
  name: "Benefits",
  components: {
    Card,
  },
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Kanit&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Nunito&display=swap");

.wrapper {
  background-color: #f6f9fc;
}

.container {
  width: 80%;
  margin: auto;
  padding-top: 80px;
  padding-bottom: 80px;
}

.container h1 {
  font-family: 'Kanit', sans-serif;
  font-size: 48px;
  text-align: center;
  margin-bottom: 80px;
}

.benefits-list {
  display: flex;
  justify-content: center;
  align-content: center;
  flex-wrap: wrap;
}

:deep(.card) {
  display: flex;
  align-content: center;
  border-radius: 20px;
  width: 570px;
  height: 150px;
  box-shadow: 0px 8px 24px rgba(0, 0, 0, 0.15);
  padding: 32px;
  margin: 32px;
}

:deep(.card-text) {
  margin-left: 24px;
}

:deep(.card) h1 {
  font-family: 'Kanit', sans-serif;
  font-size: 24px;
  font-weight: 600;
}

:deep(.card) p {
  font-family: 'Nunito', sans-serif;
  font-size: 14px;
  color: #ababab;
}
</style>
