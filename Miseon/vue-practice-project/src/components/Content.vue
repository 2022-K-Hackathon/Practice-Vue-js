<template>
  <div class="container">
    <div>
        <!-- 뒤로가기 버튼 -->
        <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-chevron-left detail-back" viewBox="0 0 16 16">
            <path fill-rule="evenodd" d="M11.354 1.646a.5.5 0 0 1 0 .708L5.707 8l5.647 5.646a.5.5 0 0 1-.708.708l-6-6a.5.5 0 0 1 0-.708l6-6a.5.5 0 0 1 .708 0z"/>
        </svg>

        <!-- 뒤로가기 글씨 -->
        <div class="detail">상세 페이지</div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Content.vue',
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
@import '/src/css/content.css';

</style>