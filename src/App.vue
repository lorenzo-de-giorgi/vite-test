<template>
  <div>
    <HeaderComponent/>
    <MainComponent/>
  </div>
</template>

<script>
  import HeaderComponent from './components/HeaderComponent.vue';
  import MainComponent from './components/MainComponent.vue';
  export default {
    name: 'App',
    components: {
      HeaderComponent,
      MainComponent
    },
    data(){
      return{
        
      }
    },
    methods: {
      
    },
    computed: {
      
    },
  }
</script>

<style lang="scss" scoped>
  h1{
    color: red;
  }
</style>