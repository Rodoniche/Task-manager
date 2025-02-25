

<template>
  <Header/>
  <task/>
  <Footer/>
  
  
</template>


<script>
  import Header from './components/header.vue'
  import Footer from './components/footer.vue'
  import task from './components/task.vue'

  export default {
    components: { Header, Footer, task },
    data() {
      return {
        tasks: [],
        name: '',
        deadline: '',
        describtion: ''
      }
    }
  }
</script>

<style scoped>

</style>
