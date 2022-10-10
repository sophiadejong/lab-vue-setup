<template>
    <button @click="helloWorld()">Hello {{sitename}}</button>
</template>

<script>

export default {
    data () {
        return {
          sitename: "World"
        }
    },
    methods: {
        helloWorld() {
            console.log('Hello World')
    }
  }
}


// export default {
//   name: "HelloWorld",
//   props: {
//     msg: String,
//     message2: String,
//   },
//   data() {
//     return {
//       message2:
//         "Lorem ipsum",
//     };
//   },
// };
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3,
h1 {
  color: pink;
}

h2 {
  font-style: bold;
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
