<template>
  <div class="dashboard-container">
    hello info component
    <button type="button" @click="add()">添加</button>
  </div>
</template>

<script>

export default {
  name: 'Customer',
  methods:{
    add(){
      alert('addd hhf ')
    }
  }
} 
</script>

<style lang="scss" scoped>
.dashboard {
  &-container {
    margin: 30px;
  }
  &-text {
    font-size: 30px;
    line-height: 46px;
  }
}
</style>
