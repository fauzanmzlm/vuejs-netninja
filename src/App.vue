<template>
  <h1>{{ title }}</h1>
  <ModalComponent :header="header" :text="text" theme="sale" />
</template>

<script>
import ModalComponent from './components/ModalComponent.vue'

export default {
  name: 'App',
  components: {
    ModalComponent
  },
  data() {
    return {
      title: 'My First Vue App :)',
      header: 'Sign Up For The Giveaway!',
      text: 'Lorem Ipsum Donor Sit Amet',
    }
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
h1 {
  border-bottom: 1px solid #ddd;
  display: inline-block;
  padding-bottom: 10px;
}
</style>
