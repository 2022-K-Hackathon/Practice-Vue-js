<template>
  <div class="container" v-if="contentView == false">
    <div class="main-title">My First Web App</div>

    <div class="memo" v-for="i in 4" :key="i" @click="contentView = true; $router.push('/detail')">
      <div class="memo-title">
        메모
      </div>
      
      <div class="memo-content">
        내용
      </div>
    </div>
  </div>

  <router-view v-if="contentView == true"></router-view>
</template>

<script>

export default {
  name: 'Main.vue',
  data() {
    return {
      contentView: false,
    }
  },
  components: {
  }
}
</script>

<style>

</style>