<template>
  <l-order-layout :method="getShopOrderList"></l-order-layout>
</template>

<script>
import LOrderLayout from 'components/layout/order-layout'
import { getShopOrderList } from 'api'
export default {
  components: {
    LOrderLayout
  },
  data () {
    return {
      method: getShopOrderList
    }
  }
}
</script>

<style lang="scss">

</style>
