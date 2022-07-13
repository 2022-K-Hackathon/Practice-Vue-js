<template>
  <router-view></router-view>
</template>

<script>


export default {
  name: 'App.vue',
  data() {
    return {
      title : ['첫번째 메모', '두번째 메모', '세번째 메모', '네번째 메모', '다섯번째 메모'],
    }
  },
  components: {
    
  }
}
</script>

<style>
@import './css/main.css';
@import '/src/css/content.css';

</style>
