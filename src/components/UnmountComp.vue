<template>
    <h1>beforeUnmount and unmounted</h1>
    <button v-on:click="show=!show">Toggle</button>
    <UserUnmount v-if="show"/>
</template>
<script>
import UserUnmount from './UserUnmount.vue'

export default {
    name:"UnmountComp",
    components:{
      UserUnmount  

    },
    data()
    {
        return{
            show:true
        }
    }

}
</script>
<style scoped>

</style>