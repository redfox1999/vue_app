<template>
    <div id="about">
        <h1 v-text="msg"></h1>
    </div>
</template>

<script>
export default {
    name: "About",
    data: function() {
        return {
            msg: "This is about page"
        }
    }
}
</script>

<style scoped>

h1, h2 {
  font-weight: normal;
}
</style>