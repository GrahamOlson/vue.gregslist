<template>
  <div class="hello">
    <div class="row">
      <div class="col-12">
        <h1>Dashboard</h1>
        <button type="button" class="btn btn-dark">Cars</button>
        <button type="button" class="btn btn-dark">Houses</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Dashboard',
  data () {
    return {

    }
  }
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
