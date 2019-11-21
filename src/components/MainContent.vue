<template>
  <div class="hello">
    <h1>{{ msg }}</h1>

    <Table border style="margin:10px" :columns="table_cols" :data="table_data"></Table>
  </div>
</template>

<script>
export default {
    name: 'MainContent',

    data () {
        return {
            msg: 'Welcome to Your Vue.js + iViewUI App',
            table_cols: [{title:"Name", key: "name"}, {title: "Age", key:'age'}, {title: "Address", key:"addr"}],
            //table_data: [{name: "Jack", age: 22, addr:"fdsafdsafdsafdsa"}]
            table_data: []
        }
    },

    created() {
        for(let i = 0; i < 5; i++)
            this.table_data.push({name: "Jack", age: 22, addr: "fdsafdsafdsa"})
    },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
