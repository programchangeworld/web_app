<template>
  <div class="pull-down-loading">{{loadingText}}</div>
</template>

<script>
export default {
  name: 'pullingDownLoading',
  props: {
    loadingText: String
  }
}
</script>

<style lang="scss" scoped>
.pull-down-loading{
  display: flex;
  justify-content: center;
  align-items: center;
  position: fixed;
  top: .44rem;
  left: 0;
  width: 100%;
  height: .5rem;
  color: #999;
  font-size: .14rem;
}
</style>
