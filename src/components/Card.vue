<template>
  <div class="card">
    <div class="card-image">
      <img :src="img" alt="">
    </div>
    <div class="card-text">
      <h1>{{ title }}</h1>
      <p>{{ mainText }}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Card',
  props: {
    img: String,
    title: String,
    mainText: String
  }
}
</script>