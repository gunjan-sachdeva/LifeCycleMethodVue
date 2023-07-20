<template>
<h1>beforeMount and mounted {{name}}</h1>
<h2>Working on Mount Life cycle phase</h2>
</template>

<script>
export default {
    name: "MountComp",
    data() {
        return {
            name: "Gunjan"
        }

    },
    beforeMount() {
        console.warn("beforeMount", this.$el)
    },
    mounted() {
        console.warn("beforeMount", this.$el)
    }
}
</script>

<style scoped>

</style>
