<template>
  <l-main-layout back>
    <l-part-line text="暂无评论"></l-part-line>
  </l-main-layout>
</template>

<script>
import LMainLayout from 'components/layout/main-layout'
import LPartLine from 'components/common/part-line'
export default {
  name: 'MessageComment',
  components: {
    LMainLayout,
    LPartLine
  }
}
</script>

<style lang="scss">

</style>
