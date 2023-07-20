<template>
 <HomeComp />
 <MountComp />
 <UpdateComp />
 <UnmountComp />
</template>

<script>
import HomeComp from './components/HomeComp.vue'
import MountComp from './components/MountComp.vue'
import UnmountComp from './components/UnmountComp.vue'
import UpdateComp from './components/UpdateComp.vue'




export default {
  name: 'App',
  components: {
    HomeComp,
    MountComp,
    UpdateComp,
    UnmountComp
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
