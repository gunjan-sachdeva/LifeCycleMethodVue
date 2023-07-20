<template>
    <h1>beforeCreate and created {{name}}</h1>
</template>
<script>
export default {
    name:"HomeComp",
    data()
    {
        console.warn("created");
        return{
            name:"Gunjan"
        }
    },
    beforeCreate()
    {
        //  this.name="Sachdeva"; no change will reflect
        alert("before Create");
       
    },
    created()
    {
          this.name="Sachdeva";
        alert("created");
    }
}
</script>
<style scoped>

</style>