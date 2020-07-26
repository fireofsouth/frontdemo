<!--  -->
<template>
  <div>
    <fire-panel></fire-panel>
    <div class="layui-container">
      <div class="layui-row layui-col-space15">
        <div class="layui-col-md8">list列表</div>
        <div class="layui-col-md4">
          <fire-tips></fire-tips>
          <fire-sign></fire-sign>
          <fire-hotlist></fire-hotlist>
          <fire-ads></fire-ads>
          <fire-links></fire-links>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Panel from '@/components/Panel'
import Tips from '@/components/sidebar/Tips'
import Sign from '@/components/sidebar/Sign'
import HotList from '@/components/sidebar/HotList'
import Ads from '@/components/sidebar/Ads'
import Links from '@/components/sidebar/Links'

export default {
  name: 'home',
  components: {
    'fire-panel': Panel,
    'fire-tips': Tips,
    'fire-sign': Sign,
    'fire-hotlist': HotList,
    'fire-links': Links,
    'fire-ads': Ads
  }
}
</script>
<style lang='scss' scoped>
</style>
