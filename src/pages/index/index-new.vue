<template>
  <div class="index-bar">
    <div class="top-box">
      <div class="location">
        <span class="cityname"></span>
        <span class="iconfont icon-arrow-down"></span>
      </div>
      <div class="search-input">
        <span class="iconfont icon-search"></span>
        <span class="text">大家正在搜：{{searchHotWords}}</span>
      </div>
      <div class="sns" @tap="tosns">
        <span class="iconfont icon-zixun"></span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      searchHotWords: 'test'

    }
  },
  methods: {
    tosns () {
      console.log('sns')
    }
  }
}
</script>

<style>
.index-bar {
  width: 100%;
  height: 142px;
  overflow: hidden;
}
</style>


