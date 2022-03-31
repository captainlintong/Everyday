<template>
  <div class="home">
    <h1 class="h1">一剪梅·红藕香残玉簟秋</h1>
    <div>红藕香残玉簟秋。</div>
    <div>轻解罗裳，</div>
    <div>独上兰舟。</div>
    <div>云中谁寄锦书来，</div>
    <div>雁字回时，</div>
    <div>月满西楼。</div>
    <div>花自飘零水自流。</div>
    <div>一种相思，</div>
    <div>两处闲愁。</div>
    <div>此情无计可消除，</div>
    <div>才下眉头，</div>
    <div>却上心头。</div>
    <div class="blog">
      <p><a href="https://www.jiumodiary.com/">推荐网站：鸠摩搜索</a></p>
      <a href="https://captainlintong.github.io/">我的博客</a>
    </div>
  </div>
</template>

<script lang="ts">
import { Vue } from 'vue-class-component';
export default class Home extends Vue {}
</script>
<style lang="scss">
.home {
  width: 100%;
  padding: 20px 30px;
  overflow: auto;
  div {
    width: 100%;
    text-align: center;
    margin-bottom: 10px;
  }
}
.h1 {
  text-align: center;
  width: 100%;
  font-size: 20px;
  margin-bottom: 20px;
}
.blog {
  text-align: right!important;;
  width: 100%;
  a {
    color: red;
  }
}
.box {
  display: flex;
  justify-content: center;
}
</style>

