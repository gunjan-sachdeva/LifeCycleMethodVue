<template>
<h1 ref="count">{{counter}}</h1>
<button @click="counter=counter+1">Update Count</button>
</template>

<script>
export default {
    name: "UpdateComp",
    data() {
        return {
            counter: 0
        }
    },
    beforeUpdate() {
        // console.log("beforeUpdate",this.counter);
        console.log("beforeUpdate", this.$refs['count'].textContent);

    },
    updated() {
        // console.log("beforeUpdate",this.counter);
        console.log("Updated", this.$refs['count'].textContent);

    }
}
</script>

<style scoped>

</style>
