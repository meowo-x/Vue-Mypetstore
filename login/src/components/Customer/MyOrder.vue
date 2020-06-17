<template>
      <div class="order">
        <el-image style="width: 120px; height: 120px;margin-top: 88px" :src="url"></el-image>
        <el-table
          id="money"
          :loading="loading"
          ref="checkedCart"
          :data="order"
          tooltip-effect="dark"
          style="width: 90%;left: 5%">
<!--          @selection-change="handleSelectionChange"-->
        </el-table>
    </div>
</template>


<script>
    export default {
        data() {
            return {
              url: 'http://qbyy9dziv.bkt.clouddn.com/order.png',
              order:[]
            }
        },

        components: {}
    }
</script>

<style scoped>
  .order {
    width: 100%;
    height: auto;
    background-color: rgba(255, 165, 51, 0.49);
  }
</style>
