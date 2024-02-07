<script>
import AppJumbo from './components/AppJumbo.vue';
export default{
  data(){
    return{
      title: 'La mia prima app con Vite!'
    }
  },
  components:{AppJumbo},
};

</script>

<template>
  <div>
    <h1>{{ title }}</h1>
  </div>
  <div class="Jumbo">
    <AppJumbo></AppJumbo>
  </div>
</template>

<style>
h1{
  color: blueviolet;
}
</style>