<template>
  <div>
    <Background />
    <div class="container">
      <h1>Ateliers</h1>
    </div>
  </div>
</template>

<script>
import Background from '../components/Background'
export default {
  components: {
    Background,
  },
  data() {
    return {
      srcImage: require('@/assets/images/img1.jpg'),
    }
  },
}
</script>

<style scoped>
.container {
  color: #fff;
}
.bg {
  background-image: url('~assets/images/bg-3.jpg');
}
</style>
