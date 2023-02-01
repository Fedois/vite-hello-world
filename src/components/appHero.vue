<script>
export default {
  data() {
    return {
      img: 'https://images.squarespace-cdn.com/content/v1/5c0f697e9d5abb8c65cd6857/1599032187414-92U41D7HVIIFVCHHBDA3/Artboard+2.png?format=1000w'
    }
  }
}
</script>

<template>
  <div>
    <img :src="img" :alt="img">
  </div>
</template>

<style scoped>
h1 {
  font-weight: bold;
  color: black;
  text-decoration: underline;
}
</style>
