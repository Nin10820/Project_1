<template>
  <div class="shop">
    <Banner></Banner>
    <Categories></Categories>
    <grLeft></grLeft>
    <listproduct></listproduct>
  </div>
</template>

<script>
import Banner from "@/components/shop/Banner";
import Categories from "@/components/shop/Categories";
import grLeft from "@/components/shop/GroupProductLeft";
import listproduct from "@/components/shop/ListProduct";

export default {
  components: {
    Banner,
    Categories,
    grLeft,
    listproduct
  },
};
</script>
<style lang="scss">
</style>