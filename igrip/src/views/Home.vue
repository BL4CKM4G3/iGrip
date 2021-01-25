<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/imgHome.png" id="imgHome">
    <HelloWorld msg="Welcome to iGrip!"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss" scoped>
.home {
  margin-top: 2rem;
}
#imgHome {
  border-radius: 20px;
}
</style>
