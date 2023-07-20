<template>
    <h1 ref="user">User component</h1>
</template>
<script>
export default {
    name:"UserUnmount",
    beforeUnmount(){
        // console.log("before Unmount");
        console.log("before Unmount",this.$refs['user']);
    },
    unmounted()
    {
        // console.log("unmounted");
        console.log("Unmounted",this,$refs['user']);
    }
}
</script>
<style scoped>

</style>