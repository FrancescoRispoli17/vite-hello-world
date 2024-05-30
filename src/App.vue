<script>
import Header from './components/HeaderComponent.vue';
import Jumbo from './components/Jumbotron.vue';
import "bootstrap/dist/css/bootstrap.min.css";
export default{
  name:'MyApp',
  data(){
    return {
      title:'aaaaaaa',
    }
  },
  components:{
    Header,
    Jumbo,
  }
};

</script>

<template>
  <Header />
  <Jumbo/>
</template>

<style scoped>

</style>
