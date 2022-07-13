<template>
  <div class="container">
    <div class="main-title">My First Web App</div>

    <div class="memo" v-for="i in title" :key="i">
      <div class="memo-title">
        {{i}}
      </div>
      
      <div class="memo-content">
        
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Main.vue',
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
@import '/src/css/main.css';

</style>