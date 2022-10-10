<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>{{message2}}</h2>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
    message2: String,
  },
  data() {
    return {
      message2: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quisquam, quidem.',
    }
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3, h1 {
  margin: 40px 0 0;
  color: pink;
}

h2 {
  padding: 20px;
  font-style: oblique;
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

