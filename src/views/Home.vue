<template>
  <div class="home">
    <h1 class="h1">《爱》</h1>
    <div class="indent">这是真的。</div>
    <div class="indent">有个村庄的小康之家的女孩子，生得美，有许多人来做媒，但都没有说成。那年她不过十五六岁吧，是春天的晚上，她立在后门口，手扶着桃树。她记得她穿的是一件月白的衫子。对门的年轻人同她见过面，可是从来没有打过招呼的，他走了过来。离得不远，站定了，轻轻的说了声：“哦，你也在这里吗？”她没有说什么，他也没有再说什么，站了一会，各自走开了。</div>
    <div class="indent">就这样就完了。</div>
    <div class="indent">后来这女子被亲眷拐子卖到他乡外县去做妾，又几次三番地被转卖，经过无数的惊险的风波，老了的时候她还记得从前那一回事，常常说起，在那春天的晚上，在后门口的桃树下，那年轻人。</div>
    <div class="indent">于千万人之中遇见你所遇见的人，于千万年之中，时间的无涯的荒野里，没有早一步，也没有晚一步，刚巧赶上了，那也没有别的话可说，惟有轻轻的问一声：“哦，你也在这里吗？”</div>
    <div class="box">
      <audio controls autoplay loop preload="auto" id="audio">
        <source src="~@/assets/audio/boy.mp3" type="audio/mpeg">
      </audio>
    </div>

    <div class="blog"><a href="https://captainlintong.github.io/">我的博客</a></div>
  </div>
</template>

<script lang="ts">
import { Dialog } from 'vant';
import { Vue } from 'vue-class-component';
Dialog({ message: '没有人知道明天会发生些什么' })
export default class Home extends Vue {}
</script>
<style lang="scss">
.home {
  width: 100%;
  padding: 20px 30px;
  overflow: auto;
}
.h1 {
  text-align: center;
  width: 100%;
  font-size: 20px;
}
.home .indent {
  text-indent: 2em;
  font-size: 20px;
  margin-bottom: 10px;
  word-break: break-all;
}
.blog {
  text-align: right;
  a {
    color: red;
  }
}
.box {
  display: flex;
  justify-content: center;
}
</style>

