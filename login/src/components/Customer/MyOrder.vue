<template>
      <div class="order">
        <el-image style="width: 150px; height: 100px;margin-top: 86px" :src="url"></el-image>
        <el-card
          style="width: 90%;left: 5%">
        </el-card>>
    </div>
</template>


<script>
    export default {
        data() {
            return {
              url: 'http://qbyy9dziv.bkt.clouddn.com/order.png',
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
