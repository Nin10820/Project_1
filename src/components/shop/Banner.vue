<template>
  <div>
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
      <ol class="carousel-indicators">
        <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
      </ol>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <div class="banner bg-opacity-black bg-1">
            <h1 class="pb-3">Rau sạch thủy canh</h1>
            <p
              class="px-5"
            >Lorem ipsum dolor sit, amet consectetur adipisicing elit. Magnam numquam consequuntur, r adipisicing elit. Voluptate fugit iure nulla aliquam distinctio aut adipisci voluptate</p>
            <button class="btn-primary btn">Buy now</button>
          </div>
        </div>
        <div class="carousel-item">
          <div class="banner bg-opacity-black bg-2">
            <h1 class="pb-3">Rau sạch thủy canh</h1>
            <p
              class="px-5"
            >Lorem ipsum dolor sit, amet consectetur adipisicing elit. Magnam numquam consequuntur, r adipisicing elit. Voluptate fugit iure nulla aliquam distinctio aut adipisci voluptate</p>
            <button class="btn-primary btn">Buy now</button>
          </div>
        </div>
        <div class="carousel-item">
          <div class="banner bg-opacity-black bg-3">
            <h1 class="pb-3">Rau sạch thủy canh</h1>
            <p
              class="px-5"
            >Lorem ipsum dolor sit, amet consectetur adipisicing elit. Magnam numquam consequuntur, r adipisicing elit. Voluptate fugit iure nulla aliquam distinctio aut adipisci voluptate</p>
            <button class="btn-primary btn">Buy now</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
};
</script>
<style lang="scss">
.banner {
  width: 100%;
  background-attachment: fixed;
  background-clip: initial;
  background-origin: initial;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
  z-index: 0;
  padding: 13em 20em;
  color: white;
  text-align: center;
  h1 {
    font-size: 3em;
  }
  &.bg-1 {
    background-image: url("../../assets/images/banners/banner_5.jpg");
  }
  &.bg-2 {
    background-image: url("../../assets/images/banners/banner_4.jpg");
  }
  &.bg-3 {
    background-image: url("../../assets/images/banners/banner_6.jpg");
  }
}
</style>