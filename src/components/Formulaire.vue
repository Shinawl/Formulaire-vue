<template>
  <h1>Formulaire</h1>
</template>

<script>
import TextInput from './components/TextInput.vue'
import DateInput from './components/DateInput.vue'
import MsgInput from './components/MsgInput.vue'
import CheckBoxInput from './components/CheckBoxInput.vue'
import ButtonInput from './components/ButtonInput.vue'

export default {
  name: 'Formulaire',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
