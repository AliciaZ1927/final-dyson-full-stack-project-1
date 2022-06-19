<template>
  <div id="list" class="d-flex justify-content-around">
    <p class="orderNum">訂單編號</p>
    <p class="quantity">購買商品數量</p>
    <p class="price">價錢</p>
  </div>
</template>

<script>
import memberPage from "@/views/memberPage.vue";
export default {
  components: { memberPage },
};
</script>

<style scoped>
#list {
  background-color: rgb(234, 234, 234);
  padding: 1.5rem;
  border: 2px #161616 solid;
}
</style>
