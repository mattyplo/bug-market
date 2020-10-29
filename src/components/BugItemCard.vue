<template>
  <div class="hello">
    <h1>{{ bugName }}</h1>
    <img :src="image" :alt="imageName">
  </div>
</template>

<script>
import image from "../assets/cricket.jpeg";

export default {
  data: function () {
    return {
      image: image
    }
  },
  name: 'HelloWorld',
  props: {
    bugName: String,
    imageName: String,
    imagePath: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
