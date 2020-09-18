<template>
  <div class="banner">
    <div class="banner-cover">
      <div class="contain-alt">
      <p class="banner-title">Top Notch Creative Agency</p>
      <p class="banner-text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quia, quaerat.</p>
      <input class="btn" type="button" value="Get Started">
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.banner {
  background: url('~assets/images/lagos.png');
  background-position: top;
  background-repeat: no-repeat;
  background-size: cover;
  display: flex;
  flex-direction: column;
  height: 400px;
  max-width: 100%;
}

.banner-cover {
  background: rgba(0, 0, 0, 0.8);
  display: flex;
  flex-direction: column;
  height: 100%;
  width: 100%;
}

.banner-title {
  color: #fff;
  font-family: 'Berkshire Swash', cursive;
  font-size: 30px;
}

.banner-text {
  color: #fefefe;
  font-family: 'Poppins', sans-serif;
  font-size: 14px;
}

.btn {
  background: #8703bb;
  border: none;
  border-radius: 30px;
  color: #fff;
  height: 35px;
  outline: none;
  width: 150px;
}
</style>