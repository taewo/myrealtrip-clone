<template>
  <div>
    <section class="header__bg">
      <img src="https://a0.muscache.com/4ea/air/r:w775-h518-sfit,e:fjpg-c80/pictures/0ffd8594-f123-43f0-85bb-7ef88c6f0624.jpg" alt="">
      <div>
        <h1>특색 있는 숙소와 즐길 거리를<br> 예약하세요.</h1>
      </div>
    </section>
  </div>
</template>
<script>
export default {

}
</script>
<style lang='scss'>
@import '/path/to/reset-css/sass/reset';

html, body {
  margin: 0;
}

.header__bg {
  img {
    width: 100%;
    height: 250px;
    object-fit: cover;
  }
  div {
    width: 100%;
    height: 250px;
    padding: 24px;
    box-sizing: border-box;
    position: absolute;
    top: 0;
  }
  h1 {
    position: absolute;
    color: white;
    bottom: 0;
    font-size: 30px;
  }
}

</style>
